<template>
  <div class="card">
    <div class="book-info">
        <img :src="pic" alt="kitap">
        <h1 id="kitapismi">{{name}}</h1>
        <a href="/yazar" class="yazar">{{author}}</a>
        <br>
        <a href="/yayinevi">{{publisher}}</a>
        <br><br>
        <a class="add-basket"><button class="price"> <p>{{price}}</p> </button></a>
    </div>
</div>
</template>
<script>
export default {
  name: 'HelloWorld',
  props: {
    bookName: String,
    author: String,
    publisher: String,
    price: String,
    pic: Image
  }
}
</script>

<style>
    .card {
        box-shadow: 0 4px 8px 0 #e6e4e4;
        max-width: 150px;
        max-height: 50px;
        text-align: center;
        font-family: arial;
        float: left;
        margin-left: 2%;
    }
    .book-info .add-basket:hover {
        content: 'Sepete Ekle';
    }
    .book-info{
        border: none;
        max-width: auto;
        max-height: auto;
        background-color: #eeeeee;
    }
    .book-info h1, .book-info a{
        color: #e4002b;
        font-size: 12px;
        text-decoration: none;
    }
    .book-info img{
      max-width: 450px;
      max-height: 200px;
    }
    .price {
        color: #e4002b;
        font-size: 19px;
    }
    .card button {
        border: none;
        outline: 0;
        color: rgb(233, 233, 233);
        background-color: #e4002b;
        text-align: center;
        cursor: pointer;
        width: 120px;
        height: 50px;
        border-radius: 5px;
    }
    .card button:hover {
        opacity: 0.7;
    }
</style>

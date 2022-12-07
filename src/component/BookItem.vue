<template>

    <div>
        <h1> {{book.universityname}}</h1>
        <h2> {{book.Establishedyear}}</h2>
        <section id="Head"><h4> Rank: {{book.universityrank}}</h4></section>
        <section id="body"><h4> State : {{book.state}}</h4>
        <h4> City : {{book.city}}</h4>
        <h4> Zip : {{book.zip}}</h4>
        <h4> Type of University : {{book.typeofuniversity}}</h4></section>
        
    </div>

</template>

<script>




export default{
    name: 'BookItem',
    props:{
        book: Array
    }
}


</script>

<style scoped>

h2{
    text-align: center;
}
h4{
    margin: 2px;
    text-align: center;
}
h1{
    text-align: center;
}
#Head{
    background-color: #f60404;
    color: black;
    padding: 1em;

}
#body{
  background-color: #e6ff00;
}
div{
    background-color: #ffb89e;
    color: black;
    padding: 1em;
}

.red{
background-color: orangered !important;

}
.green{
    color: white;
}


</style>

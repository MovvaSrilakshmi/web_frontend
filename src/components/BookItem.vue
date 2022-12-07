<template>

    <div>
        <h1> {{book.name}}</h1>
        <h2> {{book.idno}}</h2>
        <section id="Desig"><h4> Designation: {{book.designation}}</h4></section>
        <h4> Pay : {{book.pay}}</h4>
        <h4> No of Days Worked : {{book.noofdaysworked}}</h4>
        <h4> Benefits : {{book.benefits}}</h4>
        <h4> SSN : {{book.ssn}}</h4>
        <h4> Taxes : {{book.taxes}}</h4>
        
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

h1{
    text-align: center;
}
h4{
    text-align: center;
}
#Desig{
  background-color: rgb(64, 51, 180);
  color: black;
    padding: 1em;
    text-align: center;

}
#body{
  background-color: #e6ff00;
}
div{
    background-color: #ffdd9e;
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

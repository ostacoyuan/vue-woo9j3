<template>
    <div id="educ-com">
        <div id="todo-card">
            <div class="container">
                <div class="alert alert-primary" role="alert">
                    <h1>{{ msg4 }}</h1>
                </div>
                <h2><strong>UNIVERSITY OF THE ASSUMPTION SENIOR HIGHSCHOOL DEPARTMENT, SAN FERNANDO PAMPANGA</strong></h2>
                <p>2019 - 2021</p>
                <h2><strong>HOLY ANGEL UNIVERSITY, ANGELES CITY</strong></h2>
                <p>2021 - PRESENT</p>
            </div>
        </div>
    </div>
</template>

<script>
export default{
    name:'educ-com',
    data (){
        return{
            msg4:'This is the Education Component'
        } 
    }
}


</script>

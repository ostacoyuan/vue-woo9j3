<template>
    <div id="skills-com">
        <div id="todo-card">
            <div class="container">
                <div class="alert alert-primary" role="alert">
                    <h1>{{ msg2 }}</h1>
                </div>
                <p>A 2nd year College Student and a Creative Graphic Designer with 4 years of experience working in the field of graphic design industry. A Graphic Designer apprentice of Alternative Outsourcing Innovations (ALTINNO). Highly Skilled with various programs within the Adobe Creative Suite, such as Photoshop and Premiere, with also the ability to work well within a team.</p>
                <h2><strong>Specializations:</strong></h2>
              
                <ul>
                    <li>Adobe Photoshop</li>
                    <li>Adobe Lightroom</li>
                    <li>Adobe Premiere</li>
                </ul>

            </div>
        </div>
    </div>
</template>

<script>
export default{
    name:'skills-com',
    data (){
        return{
            msg2:'This is the Skills Component'
        } 
    }
}


</script>

<template>
    <div id="Projects">
        <h1>Projects</h1>
        <div class="container">
                <div class="project_item"></div>
                 <div class="project_item"></div>
                <div class="project_item"></div>
                   <div class="project_item"></div>
                   <div class="project_item"></div>
                   <div class="project_item"></div>
                   <div class="project_item"></div>
                   <div class="project_item"></div>
        </div>
        </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    #Projects{
  margin-inline: 5%;
  box-shadow: 5px 5px 5px 5px lightgray;
  border-radius: 10px;
}

.project_item{
     width: 300px;
    height: 300px;
    border-radius: 10px;
    box-shadow: 5px 5px 5px 5px lightgrey;
}
.container{
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    gap: 20px;
    margin-bottom: 100px;
    padding: 20px;
}
</style>
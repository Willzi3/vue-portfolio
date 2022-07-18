<template>
    <div id="Contact">
        <h1>Contact</h1>
       
        <div class="container">
            <div class="row">
                <div class="col">
                     <!-- modify this form HTML and place wherever you want your form -->
        <form action="https://formspree.io/f/xpzbvwbv" method="POST">
        <label>
            Your Name:
            <input type="text" name="name">
        </label>
        <label>
            Your email:
            <input type="email" name="email">
        </label>
        <label>
            Your message:
            <textarea name="message"></textarea>
        </label>
        <button type="submit">Send</button>
        </form>
                </div>
                <div class="col">
                    <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d13233.069675818386!2d18.4926986!3d-33.9856643!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x9c746d268c8e0ad9!2sLife%20Choices!5e0!3m2!1sen!2sza!4v1658147496355!5m2!1sen!2sza" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
                </div>
            </div>
        </div>
            </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    #Contact{
  height: 100vh;
  margin-inline: 5%;
  box-shadow: 5px 5px 5px 5px lightgray;
  border-radius: 10px;
  display: flex;
  justify-content: center;
    align-items: center;
    flex-direction: column;
    margin-bottom: 100px;
    
}
form {
    display: flex;
    flex-direction: column;
    box-shadow: 2px 2px 2px 2px lightgrey;
    width: 500px;
    justify-content: center;
    align-items: center;
    gap: 10px;
    padding: 20px;
    border-radius: 10px;
    height: 400px;
    

}

button {
    width: 200px;
}

.container .row {
    display: flex;
    gap: 20px;
}
.container{
    margin-bottom: 200px;
}
</style>
<script>

    let email = '';

    function handleSubmit(){
        alert('Work email submitted: ${email}');
    }
</script>


<section class = "hero">
    <div class = "hero-text">
        <h1>
        Multipurpose Website Templates <br />
        That boost your sales
        </h1>
        <p>Empowering Your Financial Journey through Customized Asset Management Services </p>

        <div class = "hero-form">
        <input
        type = "email"
        placeholder = "Enter your work email"
        bind:value={email}
        />

        <button class = "btn btn-primary" on:click = {handleSubmit}>Get Started</button>
        </div>
        <p class="no-credit">
            <img src="/images/tickvector.png" alt="tick" width="12" height="12" style="vertical-align: middle; margin-right: 5px;" />
            No credit card required
        </p>

       
    </div>
</section>

<style>

.hero {
    padding: 4rem 2rem;
    text-align: center;
}

.hero-text h1 {
    font-family: 'Apercu', sans-serif;
    font-size: 2.5rem;
    margin-bottom: 1rem;
    color: #0F0049;
    text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.2);
}

.hero-text p {
    font-family: 'Apercu', sans-serif;
    font-size: 1rem;
    color: #111827;
    opacity: 0.5;
}

.hero-form {
    margin-top: 2rem;
    display: inline-flex;
    align-items: center;
    background: #FFFFFF;
    padding: 0.75rem 0.5rem 0.5rem 0.5rem;
    border-radius: 50px;
    width: 500px;

}

.hero-form input {
    font-family: 'Apercu', sans-serif;
    padding: 0.75rem 1.5rem;
    font-size: 1rem;
    border: none;
    border-radius: 50px;
    width: 250px;
    color: #111827;
    flex: 1;
    

}
    
.hero-form button {

    padding: 0.75rem 1.5rem;
    font-size: 1rem;
    border: none;
    cursor: pointer;
    font-weight: 400;
    border-radius: 50px; 
    text-decoration: none;
    background: #3A00FF;
    color: #fff;
    align-items: center;
    justify-content: center;
    white-space: nowrap;


}     

.hero-form input::placeholder {
    color: rgba(17, 24, 39, 0.4); /* 40% opacity */
}

.no-credit {

    margin-top: 0.5 rem;
    color: #111827;
    font-size: 0.875rem;
}

    .btn-primary {
        background: #3A00FF;
        color: #fff;
    }
</style>
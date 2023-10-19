<script>

    /*
        PART A (11 marks)

        You are going to improve the code below!

        1. The information has all been hardcoded into the page... 
        your first task is to fetch the information from the following URL:

        https://api.magicthegathering.io/v1/cards?pageSize=6&contains=imageUrl

        Refactor the code so you make use of the fetched data instead of hardcoding it. (3 marks)

        2. Some of the style information is missing... you need to add the appropriate
        CSS to make your grid match the provided image (below).  (3 marks)

        3. Refactor any repetitive or redundant code to make it more efficient and elegant. (5 marks)
    */


    import { onMount } from 'svelte'

    let cards = [];
    
    onMount(() => {
        const url = `https://api.magicthegathering.io/v1/cards?pageSize=6&contains=imageUrl`;
        fetch(`${url}`)
        .then(res => res.json)
        .then(data => {
            imgs = data.results;
        });
    });

    console.log(imgs);
</script>


 



<style>
    h1, h2{
        margin:0;
    }

    .info{
        padding:30px;
    }

    .grid{
        display:grid;        
    }
</style>

<div class="grid">
    <div>
        <img src="http://gatherer.wizards.com/Handlers/Image.ashx?multiverseid=130550&type=card" />
        <div class="info">
            <h1>Ancestor's Chosen</h1>
            <h2>Creature — Human Cleric</h2>
        </div>
    </div>
    <div>
        <img src="http://gatherer.wizards.com/Handlers/Image.ashx?multiverseid=129465&type=card" />
        <div class="info">
            <h1>Angel of Mercy</h1>
            <h2>Creature — Angel</h2>
        </div>
    </div>
    <div>
        <img src="http://gatherer.wizards.com/Handlers/Image.ashx?multiverseid=129711&type=card" />
        <div class="info">
            <h1>Angelic Blessing</h1>
            <h2>Sorcery</h2>
        </div>
    </div>
    <div>
        <img src="http://gatherer.wizards.com/Handlers/Image.ashx?multiverseid=129710&type=card" />
        <div class="info">
            <h1>Angelic Chorus</h1>
            <h2>Enchantment</h2>
        </div>
    </div>
    <div>
        <img src="http://gatherer.wizards.com/Handlers/Image.ashx?multiverseid=129671&type=card" />
        <div class="info">
            <h1>Angelic Wall</h1>
            <h2>Creature — Wall</h2>
        </div>
    </div>
    <div>
        <img src="http://gatherer.wizards.com/Handlers/Image.ashx?multiverseid=132127&type=card" />
        <div class="info">
            <h1>Aura of Silence</h1>
            <h2>Enchantment</h2>
        </div>
    </div>
</div>

<!-- REFERENCE IMAGE FOR THE FINISHED GRID -->
<img src="sba_grid.png" />
<svelte:head>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</svelte:head>

<style>

    /* 
        PART C (10 marks)
        
        DO NOT CHANGE, ADD, DELETE ANY OF THE HTML OR EXISTING STYLES.
        USE CSS SELECTORS AND PSEUDO CLASSES TO ACCESS AND ALTER THE STYLES YOU NEED (WRITE NEW STYLES);

        You need to style these fine emoji people for a Halloween party. Each has a shirt, a different kind of hat, and a mask.

        1. Colour the people! (4 marks)

            - Make the FIRST person dressed all in purple (hat, shirt and mask). 
            - Make the SECOND person dressed all in brown (hat, shirt and mask). 
            - Make the THIRD person dressed all in orange (hat, shirt and mask). 
            - Make the LAST person dressed all in darkblue (hat, shirt and mask). 

        2. Remove the 2nd and 4th masks (e.g. display none). (2 marks)

        3. They all received the wrong drink orders! Fix it... (e.g. display none) (4 marks)

            - The FIRST person should have 1 drink.
            - The SECOND person should have 3 drinks.
            - The THIRD person should have 2 drinks.
            - The LAST person should have NO (0) drinks.

        REFER TO THE IMAGE FOR THE CORRECT ANSWER. WRITE YOUR STYLES BELOW.
    */

    

</style>

<!-- REFERENCE IMAGE -->
<img src="sba_people.png" /><br/>

<!-- DO NOT ALTER ANY OF THIS HTML IN ANY WAY -->
<span class="fa-stack fa-2x">
    <i class="fa-solid fa-face-smile fa-stack-2x" style="margin-top:60%"></i>
    <i class="fa-solid fa-hat-wizard fa-stack-2x" style="color:purple"></i>
    <i class="fa-solid fa-mask fa-stack-2x" style="transform:scale(.8);margin-top:54%;filter:brightness(1.2);color:purple"></i>
    <i class="fa-solid fa-shirt fa-stack-2x" style="margin-top:130%;color:purple"></i>

    <div class="drinks">
        <i class="fa-solid fa-martini-glass fa-stack-1x" style="color:red;margin-top:200%"></i>
        <i class="fa-solid fa-martini-glass fa-stack-1x" style="color:red;margin-top:250%;display:none"></i>
        <i class="fa-solid fa-martini-glass fa-stack-1x" style="color:red;margin-top:300%;display:none"></i>
        <i class="fa-solid fa-martini-glass fa-stack-1x" style="color:red;margin-top:350%;display:none"></i>
    </div>
</span>

<span class="fa-stack fa-2x">
    <i class="fa-solid fa-face-smile fa-stack-2x" style="margin-top:60%"></i>
    <i class="fa-solid fa-hat-cowboy fa-stack-2x" style="color:brown"></i>
    <i class="fa-solid fa-mask fa-stack-2x" style="transform:scale(.8);margin-top:54%;filter:brightness(1.2); color:brown;display:none"></i>
    <i class="fa-solid fa-shirt fa-stack-2x" style="margin-top:130%;color:brown"></i>

    <div class="drinks">
        <i class="fa-solid fa-martini-glass fa-stack-1x" style="color:red;margin-top:200%"></i>
        <i class="fa-solid fa-martini-glass fa-stack-1x" style="color:red;margin-top:250%"></i>
        <i class="fa-solid fa-martini-glass fa-stack-1x" style="color:red;margin-top:300%"></i>
        <i class="fa-solid fa-martini-glass fa-stack-1x" style="color:red;margin-top:350%;display:none"></i>
    </div>
</span>

<span class="fa-stack fa-2x">
    <i class="fa-solid fa-face-smile fa-stack-2x" style="margin-top:60%"></i>
    <i class="fa-solid fa-helmet-safety fa-stack-2x" style="color:orange"></i>
    <i class="fa-solid fa-mask fa-stack-2x" style="transform:scale(.8);margin-top:54%;filter:brightness(1.2);color:orange"></i>
    <i class="fa-solid fa-shirt fa-stack-2x" style="margin-top:130%;color:orange"></i>

    <div class="drinks">
        <i class="fa-solid fa-martini-glass fa-stack-1x" style="color:red;margin-top:200%"></i>
        <i class="fa-solid fa-martini-glass fa-stack-1x" style="color:red;margin-top:250%"></i>
        <i class="fa-solid fa-martini-glass fa-stack-1x" style="color:red;margin-top:300%;display:none"></i>
        <i class="fa-solid fa-martini-glass fa-stack-1x" style="color:red;margin-top:350%;display:none"></i>
    </div>
</span>

<span class="fa-stack fa-2x">
    <i class="fa-solid fa-face-smile fa-stack-2x" style="margin-top:60%"></i>
    <i class="fa-solid fa-graduation-cap fa-stack-2x" style="color:darkblue"></i>
    <i class="fa-solid fa-mask fa-stack-2x" style="transform:scale(.8);margin-top:54%;filter:brightness(1.2);color:darkblue;display:none"></i>
    <i class="fa-solid fa-shirt fa-stack-2x" style="margin-top:130%;color:darkblue"></i>

    <div class="drinks">
        <i class="fa-solid fa-martini-glass fa-stack-1x" style="color:red;margin-top:200%;display:none"></i>
        <i class="fa-solid fa-martini-glass fa-stack-1x" style="color:red;margin-top:250%;display:none"></i>
        <i class="fa-solid fa-martini-glass fa-stack-1x" style="color:red;margin-top:300%;display:none"></i>
        <i class="fa-solid fa-martini-glass fa-stack-1x" style="color:red;margin-top:350%;display:none"></i>
    </div>
</span>
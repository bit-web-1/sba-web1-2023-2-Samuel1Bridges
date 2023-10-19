<script>

    /* 
        PART B (9 marks)
        
        1. Dogs! See the array of dogs below...

            - Add a new entry for "Domino" to the END of the array. The array should have 5 dogs after this. (1 mark)
            - Remove "Fifi" from the array ENTIRELY (i.e. delete Fifi). The array should have 4 dogs after this. (1 mark)
            - Change "Fido" to "Horatio". The array should have 4 dogs after this. (1 mark)

    */
    let my_dogs = [
        "Fido",
        "Fifi",
        "Freddy",
        "Portland"
    ]



    /* WRITE YOUR ANSWERS TO #1 HERE... */
        my_dogs.push("Domino");
        my_dogs.splice(1 , 1);
        my_dogs[0] = "Horatio";
        console.log(my_dogs);
    /*
        2. Dogs again! See the array of food below...

            - In the most robust and elegant way, update the my_dogs array so that each dog 'loves' a food (concatenate a string). (3 marks)
            - The food should alternate back and forth... i.e. dogs 1 and 3 get food 1, dogs 2 and 4 get food 2 (2 marks)
            - The entries in my_dogs should read like this at the end:

                Horatio loves chicken.
                Freddy loves beef.
                Portland loves chicken.
                Domino loves beef.
    */

    let foods = ["chicken", "beef"];

    /* WRITE YOUR ANSWERS TO #2 HERE... */
    my_dogs[0] = my_dogs[0] + "loves " + foods[0];
    my_dogs[1] = my_dogs[1] + "loves " + foods[1];
    my_dogs[2] = my_dogs[2] + "loves " + foods[0];
    my_dogs[3] = my_dogs[4] + "loves " + foods[1];
</script> 

<style>

    /*
        3. Someone is trying to use CSS variables!
        But it isn't really working out for them... can you help?
        Fix the code so the paragraph below is red. (1 mark)
    */
    :root{
        --main-color:red;
    }

    p{
        color:var(--main-color);
    }

</style>

<!-- THIS P RELATES TO #3 -->
<p>
    This should be red!
</p>
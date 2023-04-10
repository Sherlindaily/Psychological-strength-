
const Questions = [{

        id: 0,

        q: "What is capital of India?",

        a: [{ text: "gandhinagar", isCorrect: false },

            { text: "Surat", isCorrect: false },

            { text: "Delhi", isCorrect: true },

            { text: "mumbai", isCorrect: false }

         document.getElementById('op3');

    const op4 = document.getElementById('op4');
 
 

    // Providing option text 

    

    // 
    op4.value = Questions[id].a[3].isCorrect;
 

    var selected = "";
 

    // Show selection for op1

    op1.addEventListener("click", () => {

        op1.style.backgroundColor = "lightgoldenrodyellow";

        op2.style.backgroundColor = "lightskyblue";

        op3.style.backgroundColor = "lightskyblue";

        op4.style.backgroundColor = "lightskyblue";

        selected = op1.value;

    })
 

    // Show selection for op2

    op2.addEventListener("click", () => {

        op1.style.backgroundColor = "lightskyblue";

        op2.style.backgroundColor = "lightgoldenrodyellow";

        op3.style.backgroundColor = "lightskyblue";

        op4.style.backgroundColor = "lightskyblue";

        selected = op2.value;

    })
 

    // Show selection for op3

    op3.addEventListener("click", () => {

        op1.style.backgroundColor = "lightskyblue";

        op2.style.backgroundColor = "lightskyblue";

        op3.style.backgroundColor = "lightgoldenrodyellow";

        op4.style.backgroundColor = "lightskyblue";

        selected = op3.value;

    })
 

    // Show selection for op4

    op4.addEventListener("click", () => {

        op1.style.backgroundColor = "lightskyblue";

        op2.style.backgroundColor = "lightskyblue";

        op3.style.backgroundColor = "lightskyblue";

        op4.style.backgroundColor = "lightgoldenrodyellow";

        selected = op4.value;

    })
 

    // Grabbing the 
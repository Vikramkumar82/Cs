ul {
    list-style-type: none;
    margin: 0;
    padding: 0;

    display: flex; /*flexbox to align items horizontally */
    align-items: center; /* Vertically align items */
    justify-content: space-between; /* Space between items */
  }
  

li .circle {
    width: 50px;
    height: 50px;
    border-radius: 50%;
}


.logout{
    background-color: rgb(255, 255, 255);
    border-color: rgb(255, 255, 255);
    color: black;
    border-radius: 5px;
}

.chat-box{
    margin-top: 10px;
    margin-left: 10px;
    margin-right: 10px;

    background: rgba(178, 178, 178, 0.11);
    border-radius: 16px;
    box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
    backdrop-filter: blur(5.3px);
    -webkit-backdrop-filter: blur(5.3px);
    border: 1px solid rgba(178, 178, 178, 0.3);

    height: 75vh;
    overflow:scroll;
}

input{
    margin: 1em;
    margin-right: 2em;
    padding: 1em;
    width:50%;
    border-radius: 6px;
    border: 1px solid rgba(178, 178, 178, 0.3)
    
}


.send{
    margin-top: 1em;
    margin-left: 0;
    padding: 0.5em;
    margin-bottom: 1em;
}


.textarea{
    display: flex;
    justify-content: flex-start;
    align-content: flex-start;
}

.circle1 {
    width: 40px;
    height: 40px;
    border-radius: 50%;
}

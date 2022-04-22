- 👋 Hi, I’m @ShitalNile
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
ShitalNile/ShitalNile is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
body{
    background-color: #1d2630;
    height: 35%;
    width: 570px;
    margin: auto;
    top: 50%;
    left: 0;
    right: 0;
    padding: 30px 0;
    border-radius: 8px;

}

#newtask{
    position: relative;
    padding: 30px 15px;
    background: #fff;
    border-radius: 5px;
    box-shadow: 0 15px 30px rgba(0, 0, 0, 0.3);

}

#newtask input{
    border-radius: 5px;
    width: 70%;
    height: 45px;
    font-size: 15px;
    border: 2px solid #d1d3d4;
    padding: 12px;
    color: #111111;
    font-weight: 500;
    position: relative;
}

#newtask input:focus{

    outline: none;
    border-color: #19A68C;

}

#newtask button{

    position: relative;
    float: right;
    width: 70px;
    height: 45px;
    border-radius: 3px;
    font-weight: 500;
    font-size: 16px;
    background: #19A68C;
    color: #fff;
    border: none;
    outline: none;
    cursor: pointer;
}

#task{
    width: 100%;
    position: relative;
    margin-top: 40px;
    background: #fff;
    padding: 30px 20px;
    border-radius: 5px;
}

.task{
    background: #fff;
    height: 50px;
    padding: 5px 10px;
    border-radius: 0px;
    margin-top: 10px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    cursor: pointer;
    border-bottom: 2px solid #d1d3d4;
}

.task span{
    font-size: 20px;
    font-weight: 400;
    cursor: pointer;

}

.task button{
    border: none;
    background: #19A68C;
    height: 100%;
    width: 70px;
    color: #fff;
    border-radius: 5px;
    cursor: pointer;
}

.completed{
    text-decoration: line-through;
    opacity: 0.7;
}

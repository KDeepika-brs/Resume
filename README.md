.{
    box-sizing:border-box;
    margin:0;
    padding: 0;
    font-family: 'Times New Roman', Times, serif;
}
body{
    background: #00b6c4;
}
.container{
    background: #f5f5f5;
    max-width: 900px;
    margin: 5px auto;
    height: auto;
    padding: 20px;
    box-shadow: 0 2px 20px rgb(0, 0,0,0.3);
}
.header{
    text-align: left;
    }
.header h1{
margin-bottom: 2px;
}
.header h3{
    text-transform: uppercase;
    font-size: 15px;
    font-weight: 500;
}
.main{
    display:flex;
    flex-wrap: wrap;
}
.left{
    flex:1;
    padding:20px;
}
.left p{
    line-height: 2;
}
.left ul li{
    line-height: 2;
}
h2{
    background: #00b6c4;
    padding: 5px;
    color: #fff;
    margin: 5px 0;
    font-size: 20px;
    border-radius: 0 30px 30px 0;
}
.right{
    flex:1;
    padding:35px
}

.right h3{
    margin-bottom: 5px;
}

.right p{
    line-height: 2;
}

.right ul li{
    line-height: 2;

}

@media only screen and (min-width: 760px) and (max-width:991px){
    .container{
        width:95%;
        height: auto;
    }
    h2{
        font-size: 10px;
    }
}
 
@media screen and (max-width: 600px){
    .main{
        flex-direction: column;
    }
    .left,
    .right{
        flex: none;
        width: 100%;
    }
    .container{
        width: 95%;
        height: auto;
    }
    h2{
        font-size: 10px;
    }
}

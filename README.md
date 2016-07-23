# Restaurant-order
a way to request order remotly

<html>
<head>
    <title></title>
	<meta charset="utf-8" />

    <style type="text/css">
        .container{
            width  :800px ;
            margin :auto 
        }
        .titl{
            margin-top :50px ;
            font-weight :bold 
        }
        .lst{
            margin-left :-40px
        }
        .tbl {
            display :inline ;
           border :1px solid gray ;
           margin-right :-4px ;
           padding :5px 10px ;
           cursor :pointer ;
           opacity :.7

           
        }
        .tbl:hover {
            background-color :lightgray ;
            color :#FFF

        }
        .select{
            border :1px solid ;
            height :200px;
            display:flex 
        
            }
        .cat{
            width :200px;
            height :23px ;
            border-top :3px solid lightgray ;
            margin :10px 20px
        }
        .cat_txt{
            margin :10px 20px ;
            font-weight :bold ;
            opacity :.7
        }
        .lists{
            width :40%
        }
        .option{
            width :25% ;
            margin-left :80px ;
            margin-top :10px
      
        }
        .btn{
            width:25%;
           
        }
        .btn button {
              margin-top: 150px;
              margin-left: 57px;
              color :white ;
              width: 128px;
              height: 44px;
              border-radius: 10px;
              background-color :darkblue 
        }
        .tot_table{
            width :100% ;
            border  :1px solid ;
            margin-top: 23px;
            height :200px
            
        }
   
        .txt_total{
              margin-left: 615px;
              margin-top: 14px
        }

        .total button {
              margin-left: 618px;
              width: 130px;
              height: 43px;
              background-color: darkblue;
              color: white;
              border-radius: 12px

        }
        .tot_table .td{
            border-left :1px solid ;
             padding-left :5px;
             border-bottom :1px solid ;
             width:20%;
             height :20px
        }
        .lst_2{
            width:100%
        }
        .tbl_2{
           display :inline ;
           border :1px solid gray ;
           margin-right :-4px ;
           padding :5px 10px ;
           cursor :pointer ;
           opacity :.7 ;

           width:20%;


        }

    </style>


</head> 
<body>
    <div class="container">
        <h1 class="titl"> Restarant order</h1>
        <ul class="lst">
            <li class="tbl">add meal</li>
            <li class="tbl">add order</li>
            <li class="tbl">Reports</li>

        </ul>
    </div>
    <!--Start  category-->

    <div class="category">
        <div class="container">
            <div class="select">
                <div class="lists">
                    <table>
                        <tr>
                            <td><text class="cat_txt">category</text></td>
                            <td>
                                <select class="cat">
                                    <option></option>
                                    <option>A</option>
                                    <option>B</option>
                                    <option>C</option>
                                    <option>D</option>


                                </select>
                            </td>



                        </tr>
                        <tr>
                            <td><text class="cat_txt">meal</text></td>
                            <td>
                                <select class="cat">
                                    <option></option>
                                    <option>A</option>
                                    <option>B</option>
                                    <option>C</option>
                                    <option>D</option>


                                </select>
                            </td>



                        </tr>
                        <tr>
                            <td><text class="cat_txt">q</text></td>
                            <td><textarea class="cat"></textarea></td>
                        </tr>

                    </table>
                </div>
                <div class="option">
                    <input type="checkbox" name="combo" value="2LE"/>Combo.add 2LE <br /> 
                    <input type="checkbox" name="spicy" value="1LE" />Spicy.add 1LE <br />
                    <br />
                    <br />
                    <br />
                    <br />
                    <br />
                <h2>Price LE</h2>
                </div>
                <div class="btn">
                    <button >Add</button>
                </div>
            </div>

        </div>

    </div>
    <!--End category-->

</body>
</html>

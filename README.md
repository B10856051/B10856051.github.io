<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>澳洲牛點餐價格表</title>
    <style>
        h1 {
            font-weight: bolder;
            color: blue;
            text-align: center;
        }
        
        h2 {
            color: red;
            text-align: center;
        }
        
        table {
            margin: auto;
            border: 1px;
            border-style: dashed;
        }
        
        td {
            border-style: dotted;
            border-width: 1px;
            padding: 10px;
            border-color: red;
            text-align: center
        }
        
        .td-noborder {
            border-width: 0px;
        }
        
        .content {
            color: green;
            font-family: Arial;
            font-size: 18px;
        }
        
        .redcontent {
            color: red;
            font-family: Arial;
            font-size: 18px;
        }
        
        #tableTitle {
            font-weight: bolder;
            font-size: 18px;
            border-color: purple;
            color: purple;
            text-align: center
        }
    </style>
    <script>
        var x, y, a;
        document.write("<h1>澳洲牛點餐價格表</h1>");
        document.write("<h2>折扣內容：滿300的倍數打8折</h2>");
        document.write("<table>");
        for (y = 0; y <= 7; y++) {
            document.write("<tr>");
            for (x = 0, a = 0; a <= 5; x += 50, a++) {
                if (y == 0 && x == 0) {
                    document.write("<td class='td-noborder'>");
                    document.write("</td>");
                } else if (x == 0 && y != 5) {
                    document.write("<td id='tableTitle'>");
                    document.write('套餐' + a + '<br>' + y + '元');
                    document.write("</td>");
                } else {
                    if (y == 0) {
                        document.write("<td id='tableTitle'>");
                        document.write(x);
                        document.write("</td>");
                    } else {
                        if ((x * y) % 300 == 0) {
                            document.write("<td class='redcontent'>");
                            document.write('原價：' + x * y + '<br>' + x * y * 0.8);
                            document.write("</td>");
                        } else {
                            document.write("<td class='content'>");
                            document.write(x * y);
                            document.write("</td>");
                        }
                    }
                }
            }
            document.write("</tr>");
        }
        document.write("</table>");
    </script>
    </script>
</head>

<body>

</body>

</html>

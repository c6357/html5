    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>表格的使用</title>
</head>
<body>


    <h1>0 有边框的表格</h1>
    <table border="10" bgcolor="#fffacd">
        <tr>
            <td>表格1</td>
            <td>表格2</td>
            <td>表格3</td>
        </tr>

        <tr>
            <td>表格1</td>
            <td>表格2</td>
            <td>表格3</td>
        </tr>
    </table>



    <h1>1 没有边框的表格</h1>
    <table >  <!-- 或者 border="0"-->
        <tr>
            <td>表格1</td>
            <td>表格2</td>
            <td>表格3</td>
        </tr>

        <tr>
            <td>表格1</td>
            <td>表格2</td>
            <td>表格3</td>
        </tr>
    </table>



    <h1>2 表格的表头</h1>
    <table border="10">
        <tr>
            <th>单元</th>
            <th>单元</th>
            <th>单元</th>
        </tr>

        <tr>
            <td>表格1</td>
            <td>表格2</td>
            <td>表格3</td>
        </tr>

        <tr>
            <td>表格1</td>
            <td>表格2</td>
            <td>表格3</td>
        </tr>
    </table>



    <h1>3 空单于格</h1>
    <table border="10">
        <tr>
            <th>单元</th>
            <th>单元</th>
            <th>单元</th>
        </tr>

        <tr>
            <td>表格1</td>
            <td></td>
            <td>表格3</td>
        </tr>

        <tr>
            <td></td>
            <td>表格2</td>
            <td>表格3</td>
        </tr>
    </table>


    <h1>4 带有标题的表格</h1>
    <p>表格</p>
    <table border="10">
        <caption>重要表格</caption>
        <tr>
            <th>单元</th>
            <th>单元</th>
            <th>单元</th>
        </tr>

        <tr>
            <td>表格1</td>
            <td></td>
            <td>表格3</td>
        </tr>

        <tr>
            <td></td>
            <td>表格2</td>
            <td>表格3</td>
        </tr>
    </table>



    <h1>5 表格内的标签</h1>
    <table border="2">
        <tr>
            <td>表格1</td>
            <td>表格3</td>
        </tr>

        <tr>
            <td>
                <ul>
                    <li>苹果</li>
                    <li>菠萝</li>
                    <li>香蕉</li>
                </ul>
            </td>
            <td>我想吃了</td>
        </tr>
    </table>



    <h1>6 单元格的边距</h1>
    <table border="1">
        <tr>
            <td>单元1</td>
            <td>单元2</td>
            <td>单元3</td>
        </tr>
        <tr>
            <td>单元4</td>
            <td>单元5</td>
            <td>单元6</td>
        </tr>

    </table>
    <br/>
    <table border="1" cellpadding="10">
        <tr>
            <td>单元1</td>
            <td>单元2</td>
            <td>单元3</td>
        </tr>
        <tr>
            <td>单元4</td>
            <td>单元5</td>
            <td>单元6</td>
        </tr>
    </table>



    <h1>7 单元格的间距</h1>
    <table border="1">
        <tr>
            <td>单元1</td>
            <td>单元2</td>
            <td>单元3</td>
        </tr>
        <tr>
            <td>单元4</td>
            <td>单元5</td>
            <td>单元6</td>
        </tr>

    </table>

    <br/>

    <table border="1" cellspacing="10">
        <tr>
            <td>单元1</td>
            <td>单元2</td>
            <td>单元3</td>
        </tr>
        <tr>
            <td>单元4</td>
            <td>单元5</td>
            <td>单元6</td>
        </tr>
    </table>



    <h1>7 单元格的背景颜色和图像</h1>
    <table border="1" bgcolor="aqua">
        <tr>
            <td>单元1</td>
            <td>单元2</td>
            <td>单元3</td>
        </tr>
        <tr>
            <td>单元4</td>
            <td>单元5</td>
            <td>单元6</td>
        </tr>

    </table>
    <br/>
    <table border="1" background="html.jpg">
        <tr>
            <td>单元1</td>
            <td>单元2</td>
            <td>单元3</td>
        </tr>
        <tr>
            <td>单元4</td>
            <td>单元5</td>
            <td>单元6</td>
        </tr>
    </table>


    <h1>8 单元格内容排列</h1>
    <table border="1" bgcolor="aqua">
        <tr>
            <td>
                <ol>
                    <li>单元</li>
                </ol>
            </td>
            <td>
                <ol>
                    <li>单元</li>
                </ol>
            </td>
            <td>
                <ol>
                    <li>单元</li>
                </ol>
            </td>
        </tr>
        <tr>
            <td>单元4</td>
            <td>单元5</td>
            <td>单元6</td>
        </tr>

    </table>
    <br/>
    <table border="1">
        <tr>
            <td>单元4</td>
            <td>单元5</td>
            <td>单元6</td>
        </tr>
    </table>



    <h1>9 跨行跨列单元格</h1>

    <!-- 跨2列-->
    <table border="1">
        <tr>
            <td colspan="2" align="center">111</td>
        </tr>
        <tr>
            <td>222</td>
            <td>333</td>
        </tr>
    </table>


    <br/>
    <!-- 跨2列-->
    <table border="1">
        <tr>
            <td>111</td>
            <td rowspan="2">222</td>
        </tr>
        <tr>
            <td>333</td>
            <td>444</td>
        </tr>
    </table>



    <br/>
    <!-- 跨2行和跨2列结合-->
    <table border="10">
        <tr>
        <td rowspan="2">111</td>
            <td>222</td>
            <td>333</td>
        </tr>
        <tr>
            <td>444</td>
            <td>555</td>
        </tr>
        <tr>
            <td>666</td>
            <td colspan="2">777</td>
        </tr>
    </table>

</body>
</html>

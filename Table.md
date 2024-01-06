# Table
ওয়েব পেইজের ভিতর প্রায়শই তথ্যের অর্থবহ ও দৃষ্টিনন্দন উপস্থাপনার জন্য টেবিল তৈরি করার প্রয়োজন হয়। কিছু উপাত্ত ও তথ্য থাকে যেগুলো টেবিলে না হলে বোধগম্য হয় না। তাই এ ক্ষেত্রে ছক তৈরি করার জন্য ``table`` ব্যবহার করা হয়।

## Table tag সমূহ:
#### ``<table></table>`` 

কাজঃ table তৈরি করা।

উদাহরণঃ
```html
<body>

    <table border="1">
        <tr>
            <th>Header 1</th>
            <th>Header 2</th>
        </tr>
        <tr>
            <td>Row 1, Cell 1</td>
            <td>Row 1, Cell 2</td>
        </tr>
        <tr>
            <td>Row 2, Cell 1</td>
            <td>Row 2, Cell 2</td>
        </tr>
    </table>

</body>
```

Output:
<body>
    <table border="1">
        <tr>
            <th>Header 1</th>
            <th>Header 2</th>
        </tr>
        <tr>
            <td>Row 1, Cell 1</td>
            <td>Row 1, Cell 2</td>
        </tr>
        <tr>
            <td>Row 2, Cell 1</td>
            <td>Row 2, Cell 2</td>
        </tr>
    </table>
</body>

#### ``<td></<td>`` 
পূর্ণরূপঃ table data 

কাজঃ টেবিল সেল তৈরি করা।

উদাহরনঃ
```html
<body>
    <table border="1">
        <tr>
            <td>Cell 1</td>
            <td>Cell 2</td>
        </tr>
    </table>
</body>
```

আউটপুটঃ 
<body>
    <table border="1">
        <tr>
            <td>Cell 1</td>
            <td>Cell 2</td>
        </tr>
    </table>
</body>

#### ```<tr></tr>```
পূর্ণরূপঃ table row

কাজঃ টেবিল এ সারি তৈরি করা।

উদাহরনঃ
```html
<body>

    <table border="1">
        <tr>
            <td>Row 1, Cell 1</td>
            <td>Row 1, Cell 2</td>
        </tr>
        <tr>
            <td>Row 2, Cell 1</td>
            <td>Row 2, Cell 2</td>
        </tr>
    </table>

</body>
```

আউটপুটঃ
<body>
    <table border="1">
        <tr>
            <td>Row 1, Cell 1</td>
            <td>Row 1, Cell 2</td>
        </tr>
        <tr>
            <td>Row 2, Cell 1</td>
            <td>Row 2, Cell 2</td>
        </tr>
    </table>
</body>

 #### ```<th></th>```
পূর্ণরূপঃ table header

কাজঃ টেবিল এর ``heading`` দেওয়া।

উদাহরনঃ 
```html
<body>

    <table border="1">
        <tr>
            <th>Header 1</th>
            <th>Header 2</th>
        </tr>
        <tr>
            <td>Row 1, Cell 1</td>
            <td>Row 1, Cell 2</td>
        </tr>
        <tr>
            <td>Row 2, Cell 1</td>
            <td>Row 2, Cell 2</td>
        </tr>
    </table>

</body>
```

আউটপুটঃ
<body>
    <table border="1">
        <tr>
            <th>Header 1</th>
            <th>Header 2</th>
        </tr>
        <tr>
            <td>Row 1, Cell 1</td>
            <td>Row 1, Cell 2</td>
        </tr>
        <tr>
            <td>Row 2, Cell 1</td>
            <td>Row 2, Cell 2</td>
        </tr>
    </table>
</body>

#### ```<caption></caption>```
কাজঃ টাবিল এর ``caption`` দেওয়া।

উদাহরণঃ 
```html
<body>

    <table border="1">
        <caption>This is a Table Caption</caption>
        <tr>
            <th>Header 1</th>
            <th>Header 2</th>
        </tr>
        <tr>
            <td>Row 1, Cell 1</td>
            <td>Row 1, Cell 2</td>
        </tr>
        <tr>
            <td>Row 2, Cell 1</td>
            <td>Row 2, Cell 2</td>
        </tr>
    </table>

</body>
```

আউটপুটঃ
<body>
    <table border="1">
        <caption>This is a Table Caption</caption>
        <tr>
            <th>Header 1</th>
            <th>Header 2</th>
        </tr>
        <tr>
            <td>Row 1, Cell 1</td>
            <td>Row 1, Cell 2</td>
        </tr>
        <tr>
            <td>Row 2, Cell 1</td>
            <td>Row 2, Cell 2</td>
        </tr>
    </table>
</body>

## Table Border
HTML  এর টেবিল ``boder`` সহ এবং ``border`` ছাড়া ও বানানো যায়।
তবে ``border`` সহ টেবিল বানানো শ্রেয়। নিচে ``border`` সহ এবং ``border`` ছাড়া টেবিল এর উদাহরণ দেওয়া হলো। 


Border ছাড়া টেবিল 
 <b>Header 1</b>  <b>Header 2</b>
Row 1, Cell 1 Row 1, Cell 2
Row 2, Cell 1 Row 2, Cell 2

<body>
  <table border="1px">
    <caption>Border সহ টেবিল</caption>
    <tr>
      <th>Header 1</th>
      <th>Header 2</th>
    </tr>
    <tr>
      <td>Row 1, Cell 1</td>
      <td>Row 1, Cell 2</td>
    </tr>
    <tr>
      <td>Row 2, Cell 1</td>
      <td>Row 2, Cell 2</td>
    </tr>
  </table>
</body>


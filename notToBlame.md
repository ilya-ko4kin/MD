# Шпаркалка по Markdown'у


#### Заголовки
Всего есть пять уровней заголовков.  
Для объявления заголовка используется знак "#"

#### Выделение текста
*курсив*, **жирный**, 
***жирный курсив***,~~зачеркнут~~

~~все нежелательные фразы могут быть зачеркнуты~~  
кроме того, еще можно писать **ТАК** или ***так***

#### Список задач

- [x] 1 
- [ ] 2
- [x] 3
  - [ ] 4
  - [ ] 5
    - [ ] 3
    - [x] 6

#### Нумерованный список

1. один
2. два
3. три

#### Маркированный список

- первый
- второй
- третий

#### Вложенный список

1. Первый
    - второй
    - третий
2. Второй
    - третий 
    - четвертый

#### Горизонтальная линия

---


#### LaTeX

$\mu \text{ -  мат.ожидание}$

$D = \frac{\sum(x-\mu)^2}{n}$ - дисперсия

$\sigma=\sqrt{D}$ - стандартное отклонение

#### Цитаты

> first
>> second
>>> third
>>>>
>>>>>
>>>>>>
>>>>>>>phara

#### Символы
Superscript: X<sub>2</sub>，Subscript: O<sup>2</sup>

#### Цвет текста
<font color="white">This text is white!</font>  
<font color="blue">This text is blue!</font>  
<font color="red">This text is red!</font>

#### Ссылки
[ссылка на youtube](https://www.youtube.com/)

#### Сноски

Here is a simple footnote [^1].

A footnote can also have multiple lines [^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.

#### Вставка картинки
Общий шаблон: "![] (ссылка на картинку)"

![](https://upload.wikimedia.org/wikipedia/commons/thumb/7/71/McD_Big_Mac.jpg/1200px-McD_Big_Mac.jpg)

#### Вставка кода
одиночная строка `pip install`

блок кода 
```commandline
insert
```

объявлять можно любой ЯП и блоки будут подсвечены
```python
print("Привет, мир!")
```

```html
<!DOCTYPE html>
<html>
    <head>
        <mate charest="utf-8" />
        <title>Hello world!</title>
    </head>
    <body>
        <h1>Hello world!</h1>
    </body>
</html>
```

```javascript
function test(){
    console.log("Hello world!");
}
 
(function(){
    var box = function(){
        return box.fn.init();
    };

    box.prototype = box.fn = {
        init : function(){
            console.log('box.init()');

            return this;
        },

        add : function(str){
            alert("add", str);

            return this;
        },

        remove : function(str){
            alert("remove", str);

            return this;
        }
    };
    
    box.fn.init.prototype = box.fn;
    
    window.box =box;
})();

var testBox = box();
testBox.add("jQuery").remove("jQuery");
```

```sql
SELECT * FROM employee ORDER BY country_of_birth ASC/DESC;
```

## На этом всё.


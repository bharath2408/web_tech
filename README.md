# WEB TECHNOLOGY

## HTML

### BASIC HTML TEMPLATE
``` html
<!-- create simple html template with the 
help of html:5 or ! -->

<!DOCTYPE html>
<!--dcoument type: browser understand this is html file-->
<html lang="en">
  <!--<html></html> html root element-->
  <head>
    <!--<head></head> is used to specify the meta tagas and title tag
        and stylesheet link and add script.-->
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <!--Title tag is used to specify the title of the html page. -->
  </head>
  <body>
    <!--The <body> element contains all the contents of an HTML document,
        such as headings, paragraphs, images, hyperlinks, tables, lists, etc.-->
  </body>
</html>

```

### INTRODUCTION TO HTML
``` html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>introction to html</title>
  </head>
  <body>
    <!--A HTML heading or HTML h tag can be defined as a title or
         a subtitle which you want to display on the webpage. we have h1 to h6 tag but most important is h1,h2,h3 -->
    <h1>bharath</h1>
    <h2>bharath</h2>
    <h3>bharath</h3>
    <h4>bharath</h4>
    <h5>bharath</h5>
    <h6>bharath</h6>

    <!--Paragraph tag is used to display the paragraph.-->
    <p>
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ratione, labore?
    </p>

    <!--Imge tag is used to display the image by using imag url or relative path. image tag
         has two attributes( additional information to html tag.)
        1. source (src) : use to specify the image url or relative path.-->
    <img
      src="https://images.pexels.com/photos/556414/pexels-photo-556414.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
      alt="Lemon"
    />
    <img
      src="https://images.pexels.com/photos/541484/sun-flower-blossom-bloom-pollen-541484.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
      alt="sun-flower-blossom-bloom-pollen-541484"
    />
    <!--anchor tag is uesd to link the one html to another html.
     In anchor tag we have two attributes
    1. href(hyperlink reference (or) hyper reference) with the help of href we link
    the pages by using web link of relative path.
    2. target: The target attribute specifies where to open the linked document.
    3. there are following vaules to the target attribute
            _blank	Opens the linked document in a new window or tab
            _self	Opens the linked document in the same frame as it was clicked (this is default)
            _parent	Opens the linked document in the parent frame
            _top	Opens the linked document in the full body of the window
            framename	Opens the linked document in the named iframe-->
    <a href="https://mail.google.com" target="_blank"
      ><img
        src="https://images.pexels.com/photos/541484/sun-flower-blossom-bloom-pollen-541484.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
    /></a>
    <a href="./naren.html">naren</a>

    <!--below the example to link the phone number and email-->
    <a href="tel:9486846528"> call us</a>
    <a href="mailto:bharatha24kumar@gmail.com"> email us</a>
  </body>
</html>

```

### TASK 1

``` html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Task</title>
</head>
<body>
    <!--TASK_1-->
    <h2>Computer Primary Component</h2>
    <ol type="1"> <!--Order list-->
        <li>Input Device 
            <ol type="a"> <!--Order List-->
                <li>Direct Input
                    <ul type="square"> <!--Unorder List-->
                        <li>Scanner</li>
                    </ul>
                </li>
                <li>Indirect Input
                    <ul type="square"> <!--Unorder List-->
                        <li>Keyboard</li>
                        <li>Mouse</li>
                    </ul>
                </li>
            </ol>
        </li>
        <li>Output Device
            <ol type="a">
                <li>Monitor
                    <ul type="square">
                        <li>CRT Monitor</li>
                        <li>LCD Monitor</li>
                    </ul>
                </li>
                <li>Speaker</li>
            </ol>
        </li>
        <li>Processing Device
            <ol type="a">
                <li>ALU
                    <ul type="square">
                        <li>Arithemetic unit</li>
                        <li>Logic Unit</li>
                    </ul>
                </li>
                <li>CU</li>
            </ol>
        </li>
        <li>Storage Device
            <ol type="a">
                <li>Primary Stroage
                    <ul type="square">
                        <li>RAM
                            <ol type="I">
                                <li>SRAM</li>
                                <li>DRAM</li>
                            </ol>
                        </li>
                    </ul>
                </li>
            </ol>
        </li>
    </ol>

     <!--Task_2-->
    <h2>List Example</h2>
    <ol type="1">
      <!--Order list-->
      <li>
        List Item 1
        <ol type="A">
          <!--Order List-->
          <li>
            Nested List 1.1
          </li>
          <li>Nested List 1.2</li>
        </ol>
      </li>
      <li>List Item 2
        <ol type="i">
            <!--Order List-->
            <li>
              Nested List 2.1
            </li>
            <li>Nested List 2.2
                <ul type="square">
                    <li>Nested List 2.2.1</li>
                    <li>Nested List 2.2.2
                        <ul type="circle">
                            <li>Nested List 2.2.2.1</li>
                            <li>Nested List 2.2.2.2</li>
                        </ul>
                    </li>
                    <li>Nested List 2.2.3</li>
                  </ul>
            </li>
            <li>Nested List 2.3</li>
          </ol>
      </li>
      <li>List Item 3
        <ul type="disc">
            <li>item 1</li>
            <li>item 2</li>
            <li>item 3</li>
        </ul>
      </li>
    </ol>

    <ul type="none">
        <li><b>COMP 376s</b>
        <ul type="none">
            <li>Intouction to Game Programming</li>
        </ul>
        </li>
        <li>Soen287
            <ul type="none">
                <li>Web programming</li>
            </ul>
        </li>
        <li>
            This is a <sup>5</sup>test<sub>9</sub> for Assignment 1.
        </li>
    </ul>
</body>
</html>
```

# Gmail logo in css and html, without png or image
![image](https://github.com/saofi10/gmail-logo-css/assets/129125993/161022f9-83d5-4342-9654-fd6130624b43)<br>
this is how it looks like!<Br>
to use this, first copy paste this in your HTML file

```html

<!--<div class='logo'>
    <div class='left'></div>
    <div class='right'></div>
    <div class='top-l'>
        <div class='left-romboid'></div>
    </div>
    <div class='top-r'>
        <div class='right-romboid'></div>
    </div>
</div>
<br> -->
THEN add this other part in your CSS sheet
```css
body { background-color: black; }

.logo { width: 280px; height: 190px; background-color: white; display: flex; margin-left: 2rem; margin-top: 2rem; border-radius: 25px; overflow: hidden; position: relative; }

.logo .left { height: 200px; width: 60px; background-color: #4385f4; border-top-right-radius: 50%; }

.logo .right { height: 200px; width: 60px; background-color: #34a853; position: absolute; top: 0; right: 0; border-top-left-radius: 50%; }

.logo .top-r { height: 200px; width: 60px; background-color: #ea4335; position: absolute; top: -30px; transform: rotate(-130deg); right: 52px; display: flex; overflow: hidden; }

.logo .top-l { height: 200px; width: 60px; background-color: #ea4335; position: absolute; top: -30px; transform: rotate(130deg); left: 52px; display: flex; overflow: hidden;

}

.logo .top-r .right-romboid { width: 120px; height: 120px; background-color: #fbbc05; transform: rotate(130deg); position: relative; top: 100px; left: -10px; } .logo .top-l .left-romboid { width: 120px; height: 120px; background-color: #bb001b; transform: rotate(50deg); position: relative; top: 100px; left: 9px; }
</code>

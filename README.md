# HTML Code

| Sl.No|  Questions        |
|------|------------------ |
| 01.  |[Border ](#Border )|
| 02.  |[Div giống pre ](#Div-giống-pre)|
| 03.  |[Recording trong listening ](#Recording-trong-listening)|
| 04.  |[Định dạng số thứ tự đậm và có cách ](#Định-dạng-số-thứ-tự-đậm-và-có-cách)|
| 05.  |[Bullet ](#Bullet)|
| 06.  |[Dạng text input chia 2 bên ](#Dạng-text-input-chia-2-bên)|

## <a id="Border"></a>***1. Border***
```
<div style="border: 2px solid rgb(121, 111, 111); padding: 10px">
```
<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## <a id="Div-giống-pre"></a>***2. Div giống pre***
```
<div style="padding: 6px 10px; border: 1px solid #ccc; border-radius: 3px; background-color: #f9f9f9; font-size: .9em; line-height: 1.4;">
```
<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## <a id="Recording-trong-listening"></a>***3. Recording trong listening***
**Vào HTML -> Raw HTML**
```
<button
    onclick='var x=document.getElementById("idUniquedBoxContent");"none"===x.style.display?x.style.display="block":x.style.display="none";'>Recording script
</button>
<div id="idUniquedBoxContent" style="display: none;">
    Recording script.
    Recording script.
</div>
```
<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## <a id="Định-dạng-số-thứ-tự-đậm-và-có-cách"></a>***4. Định dạng số thứ tự đậm và có cách***
```
<b>1</b> &#160;
```
<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## <a id="Bulleth"></a>***5. Bullet***
```
<ul style="list-style-type:circle">
    <li>Coffee</li>
    <li>Tea</li>
    <li>Milk</li>
</ul>

<ul style="list-style-type:disc">
    <li>Coffee</li>
    <li>Tea</li>
    <li>Milk</li>
</ul>

<ul style="list-style-type:square">
    <li>Coffee</li>
    <li>Tea</li>
    <li>Milk</li>
</ul>
```
<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## <a id="Dạng-text-input-chia-2-bên"></a>***6. Dạng text input chia 2 bên***
<p align="center">
  <img src="assets/6.png" alt="Node Architecture" width="auto" />
</p>

```
<div style="display: flex;width: 100%;border-bottom: 1px solid #eee;margin:10px 0px;">
    <div style="width: 50%;">(1) It / rain / today / .</div>
    <div style="width: 50%;">
        <stringresponse answer="It’s raining today." type="ci">
            <textline size="100%" />
        </stringresponse>
    </div>
</div>
```
<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

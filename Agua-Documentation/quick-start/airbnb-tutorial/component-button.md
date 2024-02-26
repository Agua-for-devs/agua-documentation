---
description: Discover what you can do in Agua!
---

# Component: Button

#### You will start by building a button!

***



<figure><img src="../../.gitbook/assets/Airbnb_Button.png" alt=""><figcaption></figcaption></figure>



## Step 1:

***

## Screen, and Alignment

{% tabs %}
{% tab title="1." %}
{% tabs %}
{% tab title="1. Video" %}

{% endtab %}
{% endtabs %}



### **1.1.** Change -Screen's- _name_ of: "Screen"

> &#x20;**Screen's new name:**
>
> ```
> Button
> ```

{% tabs %}
{% tab title="1.1. Gif" %}

{% endtab %}
{% endtabs %}

<details>

<summary><strong>1.1. Written steps</strong></summary>

#### -Inside the Screen's _**Properties Panel**_-

#### **\[Click] the current name of the Screen and \[paste]** :

```
Button
```

* The name is located at the top of the panel, above of the _Style_ toggle.
* The new name should not contain any spaces or special characters.
* The name will be updated in the _Element Tree_ after you have \[clicked] away.

</details>



### 1.2. Set -Screen's- _Alignment_ of_:_ "Button"

> **Main:** `Axis center`
>
> **Cross:** `Axis center`

{% tabs %}
{% tab title="1.2. Gif" %}

{% endtab %}
{% endtabs %}

<details>

<summary>1.2. Written steps</summary>

#### -Inside each of the Screens' _**Properties Panel**_-

#### **A. \[Click]** **the **_**Main** Axis center_ **button,** inside the Alignment section_:_

* In the Top-Down first row of buttons, choose the Left-to-right second one.
* The items are packed  to each other toward the center.

#### **B. \[Click]** **the **_**Cross** Axis center_ **button,** inside the Alignment section_:_

* In the Top-Down second row of buttons, choose the Left-to-right second one.
* The items are packed  to each other toward the center.

</details>
{% endtab %}
{% endtabs %}





## Step 2:

***

### Div, Icon, _Alignment, and Size_

{% tabs %}
{% tab title="2." %}
{% tabs %}
{% tab title="2. Video" %}

{% endtab %}
{% endtabs %}



### 2.1. Create new child -Div- inside of the Screen: "Button"

> **New Div name:**
>
> <pre><code><strong>buttondiv
> </strong></code></pre>

{% tabs %}
{% tab title="2.1. Gif" %}

{% endtab %}
{% endtabs %}

<details>

<summary>2<strong>.1. Written steps</strong></summary>

#### -Inside the _**Element Tree**_-

#### **A. \[Click]** **the **_**Div Icon**_**:**

* The button is located at the top of the panel, below the _Screens._
* The _Icon_ will turn blue, and your pointer will change.

#### **B. Drag your pointer and click "Home":**

* The new element will appear as a child of the _Screen_.
* The _Div_ will be created with the default name "Layer #".

#### -Inside the **Properties Panel**-

#### **C. \[Click] the current name of the **_**Div**_** and \[paste] the new name**:

```
buttondiv
```

* The new name should be lowercase, without any spaces or special characters.
* The name will be updated in the _Element Tree_ after you have \[clicked] away.

</details>



### **2.2.** Create new child -Icon- inside of the Div: _"_buttondiv"

> **New Icon Name:**&#x20;
>
> ```
> buttonicon
> ```

{% tabs %}
{% tab title="2.2. Gif" %}

{% endtab %}
{% endtabs %}

<details>

<summary>2<strong>.2. Written steps</strong></summary>

#### -Inside the _**Element Tree**_-

#### **A. \[Click]** **the **_**Icon Icon**_**:**

* The button is located at the top of the panel, below the _Screens._
* The _Icon_ will turn blue, and your pointer will change.

#### **B. Drag your pointer and click "**searchmenudiv5**":**

* The new element will appear as a child of the _Screen_.
* The _Icon_ will be created with the default name "Icon #".

#### -Inside the Icon's _**Properties Panel**_-

#### **C. \[Click] the current name of the **_**Icon**_** and \[paste]**:

```
buttonicon
```

* The new name should be lowercase, without any spaces or special characters.
* The name will be updated in the _Element Tree_ after you have \[clicked] away.

</details>



### 2.3. Set -Div's- _Alignment_ of: "buttondiv"

> **Main:** `Axis center`
>
> **Cross:** `Axis center`

{% tabs %}
{% tab title="2.3 Gif" %}

{% endtab %}
{% endtabs %}

<details>

<summary>2<strong>.3. Written steps</strong></summary>

#### -Inside the Div's _**Properties Panel**_-

#### **A. \[Click]** **the **_**Main** Axis center_ **button,** inside the Alignment section_:_

* In the Top-Down first row of buttons, choose the Left-to-right second one.
* The items are packed  to each other toward the center.

#### **B. \[Click]** **the **_**Cross** Axis center_ **button,** inside the Alignment section_:_

* In the Top-Down second row of buttons, choose the Left-to-right second one.
* The items are packed  to each other toward the center.

</details>



### **2.4.** Set -Div's- _Size_ of: "buttondiv"

> **Width**_:_ `Wrap`
>
> **Height**: `Wrap`

{% tabs %}
{% tab title="2.4. Gif" %}

{% endtab %}
{% endtabs %}

<details>

<summary>2<strong>.4. Written steps</strong></summary>

#### -Inside the Div's _**Properties Panel**_-

#### **A. \[Click]** **the **_**Wrap**_** button,** inside the Height section_:_

* The vertical size of the Div will become its child's maximum combined size.
* You cannot use _Wrap size_ in the case there is a child element in _Fill size_.

#### **B. \[Click]** **the **_**Wrap**_** button,** inside the Height section_:_

* The vertical size of the Div will become its child's maximum combined size.
* You cannot use _Wrap size_ in the case there is a child element in _Fill size_.

</details>



### 2.5. Set _Icon_ of: "buttonicon"

> **Icon name:**&#x20;
>
> ```
> search
> ```

{% tabs %}
{% tab title="2.5. Gif" %}

{% endtab %}
{% endtabs %}

<details>

<summary>2<strong>.5. Written steps</strong></summary>

#### -Inside the Icon's _**Properties Panel**_-

#### \[Click] the _Icon_ container and \[paste] the _Icon_ name:

```
search
```

* You can also find it through each Material category's dropdown and \[click] it.

</details>
{% endtab %}
{% endtabs %}





## Step 3:

***

### Background Color, Radius, and Padding

{% tabs %}
{% tab title="3." %}
{% tabs %}
{% tab title="3. Video" %}

{% endtab %}
{% endtabs %}



### 3.1. Set -Div's- _Background Color_ of: "buttondiv&#x20;

> **HEX Color:**
>
> ```
> FF385C
> ```

{% tabs %}
{% tab title="3.1. Gif" %}

{% endtab %}
{% endtabs %}

<details>

<summary>3<strong>.1. Written steps</strong></summary>

#### -Inside the Div's _**Properties Panel**_-

#### **A. \[Click]** **the **_**Background**_** toggle and \[click] **_**Fill**:_

* Fill allows you to select either a material color or a gradient as background.

**B. \[Click] **_**Background color**_** and** **\[paste]** **the color**_:_

```
FF385C
```

* You can type a 6 characters HEX code without the initial #.

</details>



### 3.2. Set -Div's- _Radius_ of: "buttondiv "

> **Div's Radius:**
>
> ```
> 25
> ```

{% tabs %}
{% tab title="3.2. Gif" %}

{% endtab %}
{% endtabs %}

<details>

<summary>3<strong>.2. Written steps</strong></summary>

#### -Inside the Div's _**Properties Panel**_-

#### \[Click] the _Radius_ container, and **\[paste]** **the value**_:_

```
25
```

* The _Radius_ applies to all four sides of a _Div._
* You can also change the size value using the _up and down arrows._
* The default _Unit_ is in _Pixels._

</details>



### 3.3. Set -Div's- _Padding_ of: "buttondiv "

> **Top:** `px`
>
> ```
> 8
> ```
>
> **Bottom:** `px`
>
> ```
> 8
> ```
>
> **Left:** `px`
>
> ```
> 8
> ```
>
> **Right:** `px`
>
> ```
> 8
> ```

{% tabs %}
{% tab title="3.3. Gif" %}

{% endtab %}
{% endtabs %}

<details>

<summary>3<strong>.3. Written steps</strong></summary>

#### -Inside the Div's _**Properties Panel**_-

#### **A.** \[Click] the _Padding Top_ container and **\[type]** **the new value**_:_

* You can also change the size value using the _up and down arrows._
* The default _Unit_ is in _Pixels_, you do not need to change it.

#### **B.** \[Click] the _Padding Bottom_ container and **\[type]** **the new value**_:_

* You can also change the size value using the _up and down arrows._
* The default _Unit_ is in _Pixels_, you do not need to change it.

#### **C.** \[Click] the _Padding Left_ container and **\[type]** **the new value**_:_

* You can also change the size value using the _up and down arrows._
* The default _Unit_ is in _Pixels_, you do not need to change it.

#### **D.** \[Click] the _Padding Right_ container and **\[type]** **the new value**_:_

* You can also change the size value using the _up and down arrows._
* The default _Unit_ is in _Pixels_, you do not need to change it.

</details>



### 3.4. Set -Icon- _Size_ of: "buttonicon"

> **Icon's Radius:**
>
> ```
> 28
> ```

{% tabs %}
{% tab title="3.4. Gif" %}

{% endtab %}
{% endtabs %}

<details>

<summary>3<strong>.4. Written steps</strong></summary>

#### -Inside the Icon's _**Properties Panel**_-

#### \[Click] the _Icon Size_ container and **\[type]** **the new value**_:_

* You can also change the size value using the _up and down arrows._

</details>



### 3.5. Set -Icon- _Color_ of: "buttonicon"

> **HEX Color:**
>
> ```
> E0E0E0
> ```

{% tabs %}
{% tab title="3.5. Gif" %}

{% endtab %}
{% endtabs %}

<details>

<summary>3<strong>.5. Written steps</strong></summary>

#### -Inside the Icon's _**Properties Panel**_-

#### **\[Click] **_**Icon Color**_** and** **\[Type]** **the color**_:_

* You can type a 6 characters HEX code without the initial #.
* You can select either a material color or a gradient.

</details>
{% endtab %}
{% endtabs %}





## Step 4:

***

### Create Component, and preview

{% tabs %}
{% tab title="4." %}
{% tabs %}
{% tab title="4. Video" %}

{% endtab %}
{% endtabs %}



### **4.1.** _Create Component:_

{% tabs %}
{% tab title="4.1. Gif" %}

{% endtab %}
{% endtabs %}

<details>

<summary>4<strong>.1. Written steps</strong></summary>

#### -Inside the **Properties Panel**-

#### \[Click] the "Create a Component" blue button.

* You can only create Components out of Divs.

</details>



### **4.2.** Define _Component Name:_

> `horizontaldivider`

{% tabs %}
{% tab title="4.2. Gif" %}

{% endtab %}
{% endtabs %}

<details>

<summary>4<strong>.2. Written steps</strong></summary>

#### -Inside the Create Component **Menu**-

#### \[Type] the _Component_ name.

* The default name provided is the name of the Div.
* You can use either use lowercase, uppercase, numbers or spaces.

</details>



### 4.3 Preview Component

{% tabs %}
{% tab title="4.3. Gif" %}

{% endtab %}
{% endtabs %}
{% endtab %}
{% endtabs %}





## Project Progress:

***

### Save



{% tabs %}
{% tab title="Save" %}
#### **\[Click]** **the **_**Save Button**_

{% tabs %}
{% tab title="Gif" %}

{% endtab %}
{% endtabs %}
{% endtab %}
{% endtabs %}





## Code Review:

***

### IDE

{% tabs %}
{% tab title="Code Review" %}
{% tabs %}
{% tab title="Video" %}

{% endtab %}
{% endtabs %}



#### **1. Open the project folder in your IDE**

{% tabs %}
{% tab title="1. Gif" %}

{% endtab %}
{% endtabs %}



#### 2. Open /.agua/generated folder

{% tabs %}
{% tab title="2. Gif" %}

{% endtab %}
{% endtabs %}



#### 3. Open /src/agua/pages/button

{% tabs %}
{% tab title="3. Gif" %}

{% endtab %}
{% endtabs %}



#### 4. Review _button.jsx_ and screen.module.css

{% tabs %}
{% tab title="4. Gif" %}

{% endtab %}
{% endtabs %}
{% endtab %}
{% endtabs %}

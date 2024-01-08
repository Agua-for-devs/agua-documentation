# Deploy Locally

{% tabs %}
{% tab title="LocalHost" %}
<figure><img src="../../../.gitbook/assets/Agua_Apple_Demo_LocalHost.png" alt=""><figcaption></figcaption></figure>

In order to deploy your Agua project locally open the folder in your favorite IDE:

* Replace in the `package.json` the following `"scripts"`:

```json
"start": "react-scripts --openssl-legacy-provider start",
"build": "react-scripts --openssl-legacy-provider build",
```

<figure><img src="../../../.gitbook/assets/Agua_Apple_Demo_VS_Code.png" alt=""><figcaption></figcaption></figure>

Then, inside the Terminal:

* `npm install`
* `npm start`

Finally, open your respective localhost tab in Google Chrome.
{% endtab %}
{% endtabs %}



## Need Help?

Contact us directly!

* Email [support@agua.dev](mailto:support@agua.dev).
* Book a [meeting with our founders](https://agua.tools/meetings/developers/onboarding).
* Chat with us on [WhatsApp](https://wa.me/12396883277).

Also,

* Check out our [FAQ](../../../help-and-community/faq.md).



{% hint style="info" %}
**Help us improve our docs!**

* If there are any topics you'd like us to add to our documentation, please share your feedback in our [Roadmap](https://roadmap.agua.app/).
* Edit this page in our [GitHub Repo](https://github.com/Agua-for-devs/agua-documentation) to fix an error or add an improvement to our documentation in a merge request.
{% endhint %}

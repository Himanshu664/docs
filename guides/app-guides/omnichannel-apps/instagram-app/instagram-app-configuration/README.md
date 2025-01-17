# Instagram App Configuration

To access the settings, go to **Administration** > **Apps**.

as shown below:

![](<../../../../../.gitbook/assets/2021-11-20\_23-29-48 (1).png>)

Search Instagram under the **Installed** tab in **Apps** menu on your Rocket.Chat administration panel, as shown below:

![](<../../../../../.gitbook/assets/2021-12-28\_21-03-31 (2).png>)

Click open your Instagram app to see the settings available to you as an administrator:&#x20;

Following are the settings available:

1\.  You can choose to display the agent's name or username:

![](../../../../../.gitbook/assets/2021-12-29\_17-04-47.png)

2\. You can enable/disable file sharing and also set a limit for maximum upload size:

![](<../../../../../.gitbook/assets/2021-12-29\_17-05-48 (6).png>)

3\. And you can select the type of files you wish the Agents and your Contacts can share under **Accepted Media Types**

![](../../../../../.gitbook/assets/2021-12-29\_17-32-22.png)

4\.  Delete messages once it has been "Unsend" from Instagram

![](../../../../../.gitbook/assets/2021-12-29\_17-34-16.png)

### Handover protocol&#x20;

If you have multiple Facebook app connected to a single Facebook account, then Facebook allows those apps to participate in a conversation by passing control of the conversation between them. This feature is known as Handover protocol and the documentation for this feature can be found [here](https://developers.facebook.com/docs/messenger-platform/instagram/features/handover-protocol). If you are using Handover protocol on your account, then this Instagram app allows you to perform some of the handover operations. There are two settings that control this behavior explained below:

5\. **Instagram Handover Protocol Action:**

It defines the action which should be performed while sending an agent's message to a thread, in order to get access to the thread.

![](../../../../../.gitbook/assets/2021-12-29\_17-42-55.png)

{% hint style="info" %}
**Take Thread Control** action will only work if you've configured Rocket.Chat Omni-gateway app as a **Primary Receiver** from Facebook Apps page settings.
{% endhint %}

6\. **Instagram Handover Protocol Metadata:**

It defines the metadata to be passed along with thread control action requests. You can use this to pass some custom payload to other apps.

![](../../../../../.gitbook/assets/2021-12-29\_17-43-33.png)

7\. Hit **Save Changes** to save your settings

![](<../../../../../.gitbook/assets/2021-12-29\_17-48-45 (3).png>)

Your Instagram app is successfully configured and you can see the new Instagram channel upon closing the administration panel, as shown below:

![](../../../../../.gitbook/assets/2021-12-29\_17-56-37.png)

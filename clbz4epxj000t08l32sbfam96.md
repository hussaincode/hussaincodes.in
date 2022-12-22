# How to host a website on GitHub with custom domain

In this article, we are going to learn how we can host a website on a GitHub page with a custom domain name.

I will upload my portfolio website on GitHub step by step.

First of all, we need to code your website and collect all the file and upload it to the GitHub repository.

If you don't know how to upload your code to the GitHub repository then let me know in the comment section, and I will write an article on the same.

Once the code is uploaded to the GitHub repository, Goto the same repository as shown in the below screenshot.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671711978124/Nk2EwvIPM.PNG align="center")

In the above screenshot, we can see a lot of repositories are there. I am going to upload myPortfolio website so I will click on the same.

Once we will click on the repository that we want to upload we will get to see a setting icon as shown in the below screenshot.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671712299113/NxmWSoObe.PNG align="center")

After clicking on the setting, we will find a section on the left side call pages. we will on that as shown in the below screenshot.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671712421421/rg9xFyAGq.PNG align="center")

Once we click on pages, we will see a source, we need to click on the dropdown and select "Deploy from a branch" as shown in the below screenshot.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671712589881/uZrgX7XR_.PNG align="center")

After that, we need to select the branch as the main and the folder as /(root) as shown in the below screenshot.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671712738985/m73XN7B92.PNG align="center")

After selecting the branch and folder, we will save it.

Once it's saved, we will go to our GitHub account settings as shown below.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671712906007/tnmfdc0AR.PNG align="center")

Then we will click on the pages on the left side as shown in the below screenshot.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671712971749/qjKgltncO.PNG align="center")

When we click on pages, we will see a button called add a domain. we will click on that button as shown in the below screenshot.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671713111701/sBHc_tfKG.PNG align="center")

After clicking on Add a domain button, we will see a field where we need to give the custom domain name that we would have purchased from GoDaddy or any other domain name provider.

In my case, I have purchased from GoDaddy and my custom domain name is [hussaincode.in](https://hussaincode.in/) so, I have given the same name as shown in the below screenshot.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671713384116/ZK6zYUa1V.PNG align="center")

And then we can click on "Add a domain" button as shown above.

Once we will click on Add a domain button we will get some DNS TXT records as shown in the below screenshot that we need to add to our domain name provider like in my case on GoDaddy.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671713572160/vXOKSqVVk.PNG align="center")

We will copy this hostname and TXT record value and will go to our domain name provider and find the domain name DNS record.

First, we will go to the GoDaddy website and log in through our id and click on my product as shown below.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671713803895/t_4EB89JF.PNG align="center")

Then we will go to the DNS of our domain name that we want to set up on the GitHub page as shown below.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671713889773/q-BTtpXJc.PNG align="center")

Once we click on DNS, we will find all the DNS records. In that record, we need to add the TXT record as shown below.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671713981838/BAp_vPKxw.PNG align="center")

After clicking on add, we need to select the TXT record and put the hostname and its value that we copied from the GitHub TXT record during adding a domain.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671714103219/EewLYk31A.PNG align="center")

Once it's done we will save it and look for the CNAME record in the DNS if it's there we need to edit it and if it's not there we need to add the CNAME record and give the value as "**hussaincode.github.io"** where hussaincode is my username, you can check your username from your GitHub profile and change it accordingly.

Select all the values same as shown below just change the hussaincode with your username.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671714431728/KZQv8-j-y.PNG align="center")

We will check all the values if it's correct we will save them and then we will look for the "A" record in the DNS and give the value from this [GitHub](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site) documentation as shown below.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671714630090/854vcMgKZ.PNG align="center")

After that, we will save this and come back to our repository settings again and will go to the pages.

And then at last we can see the custom domain field is there, we will give our custom domain name in that field and save it as shown below.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671714848499/_Dc9r8vgk.PNG align="center")

It will show as a DNS check in progress. We will wait for some time and it will show as the DNS check is successful as shown below

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671715090930/yl6F8av-u.PNG align="center")

Once DNS is successful, our website will go live. we can check on our custom domain our website will be up and running.

In my case, my site [hussaincode.in](https://hussaincode.in/) is up and running as shown in the below screenshot.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671715281985/VCKPjhib5.PNG align="center")

**Hurray, Our site is up and running using GitHub pages without and hosting coast.**

*If you have any doubt or get stuck at any point, comment it and I will try to help as much as possible.*

<mark>Thank you all for reading this article, Hope it helps.</mark>
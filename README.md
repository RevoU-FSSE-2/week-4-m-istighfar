# Website Deployment & Custom Domain - Week 4

## Link to Website

### [https://antariksa.site/](https://antariksa.site/)


---

## 🛠️ Deployment Setup

### 1. Sign Up / Log In to Netlify

![ss99](/img2/Screenshot%20(99).png)

If you don't have an account yet, you must register first. This time, do the sign up option with your GitHub account.

![ss100](/img2/Screenshot%20(100).png)

After signing in, you will see the netlify dashboard page as shown below.

![ss102](/img2/Screenshot%20(102).png)

### 2. Project Setup

- Import project by navigating to **Sites** and click **Add new site > Import an existing project**.

![ss103](/img2/Screenshot%20(103).jpg)

- Choose one of the Git providers, this time we will use GitHub.

![ss104](/img2/Screenshot%20(104).png)

- Select a repository to connect.

![ss106](/img2/Screenshot%20(106).png)

- Leave the settings at default and click **Deploy site**.

![ss108](/img2/Screenshot%20(108).png)

- Congrats! Your page should look like as shown below and the site can be accessed by clicking the higlighted link next to your site preview.

![ss109](/img2/Screenshot%20(109).png)

## 🌐 Custom Domain Setup

To use a custom domain, you need to purchase a domain name through a Domain Name Registrar.

For this case, we will be using Niagahoster.

![ss93](/img2/Screenshot%20(93).png)

### 1. Buy a domain

- Type your prefered domain name on the search bar. A suggestion will be shown if its available (or scroll down for more domain alternatives).
- Click **Pilih** on your prefered name to continue check-out page.

![ss94](/img2/Screenshot%20(94).png)

- Select your usage duration for the domain name, then click **Lanjutkan**.

![ss95](/img2/Screenshot%20(95).png)

- You will be redirected to select payment method and complete the transaction.

![ss96](/img2/Screenshot%20(95).png)

- After completing your payment, you should be greeted with a page as shown below. Congrats! You have successfuly purchased your domain name!

![ss119](/img2/Screenshot%20(119).png)

### 2. Clouflare Setup

- If you don't have an account yet, you must register first.

![ss110](/img2/Screenshot%20(110).png)

- On the top navigation bar, click **Add site**, then type your purchased domain name at Niagahoster and click the **Add site** button.
- You will be redirected to select a Cloudflare Plan. Select the **Free** Plan and click **Continue**.

![ss114](/img2/Screenshot%20(114).png)
![ss116](/img2/Screenshot%20(116).png)

### 3. Change Nameservers 

- Follow the instructions given by Cloudflare to replace the two nameservers currently in use on Niagahoster.

![ss118](/img2/Screenshot%20(118).png)

- On the previous Niagahoster page, under **Overview Domain**, click the **Ubah Nameserver** button. Replace Nameserver 1 & 2 with nameserver from Cloudflare as shown below, then click **Simpan**.

![ss122](/img2/Screenshot%20(122).png)

- Go back to the Cloudflare Dashboard and wait for it to process the nameservers.

### 3. Custom Domain Setup

- On the sidepanel, Go to the **DNS > Records** page and click **Add record**.
- Add the CNAME with your Netlify link as shown below, then click **Save**.

![ss129](/img2/Screenshot%20(129).png)

- Go to your Netlify project page and click **Set up a custom domain**.

![ss130](/img2/Screenshot%20(130).png)

- Type your purchased domain name.

![ss132](/img2/Screenshot%20(132).png)

- It will take a while before you can access the site. Refresh the page to check if the site is active as shown below. Congrats! You have finished setting up your custom domain!

![ss135](/img2/Screenshot%20(135).png)

# Evaluating Financial Health

With the help of fellow friends/coworkers, I decided to start a fintech consulting firm a few months ago that focuses on projects to benefit local communities. Just recently, we won our first contract with a large credit union. The project the credit union has put forth for us in the contract entails building a tool to help credit union members evaluate their financial health. Specifically, the credit union board wants the members to be able to do two things. First, they should be able to assess their monthly budgets and second, they should be able to forecast a reasonably effective retirement plan based on their current holdings of cryptocurrencies, stocks, and bonds. The chief technology officer (CTO) of the credit union wanted our firm to develop a prototype application to present at the union's next assembly. After lots of hard work we are excited to finally share! 

---

## *Technologies*

- **Programming Language:** Python
- **Libraries:** Pandas, OS, Json, Dotenv, alpaca_trade_api, MCForecastTools, Matplotlib
- **Framework:** JupyterLab, Python
- **Operating Systems:** Mac OS, Microsoft Windows

---

## *Installation Guide*

**First things first:**
If you don't have jupyter lab or python installed..
**[Install and run JupyterLab](https://jupyter.org/install)**,
**[Install Python](https://www.python.org/downloads/)**
- **Now to clone this repository so you can open it up in JupyterLab:**
- **1:** Copy URL of this repo ----> <img width="200" alt="Screenshot 2023-04-17 at 2 00 08 PM" src="https://user-images.githubusercontent.com/123714457/232610445-b7b7b5ff-f261-4b83-bf71-ae09bab3a63d.png">
- **2:** Create a folder where you will clone this repo. As an example, I created a folder 'Evaluate_Financial_Health' in my desktop ----> <img width="40" alt="Screenshot 2023-04-17 at 2 01 00 PM" src="https://user-images.githubusercontent.com/123714457/232610664-677709bc-521b-4d98-a6d6-4130592af985.png">
- **3:** In the terminal, clone the repo into the newly created folder using the copied URL of the repo in the terminal using 'git clone', make sure your working directory is in the newly created folder ----> <img width="450" alt="Screenshot 2023-04-17 at 2 32 21 PM" src="https://user-images.githubusercontent.com/123714457/232616260-0013e619-bb73-4bfb-9d3b-94ea93e4a5b1.png">
- **4:** In the terminal, make sure you are still in the working directory where you just cloned the repo, then type 'jupyter lab --ContentsManager.allow_hidden=True' and hit enter ----> <img width="420" alt="Screenshot 2023-04-17 at 2 41 43 PM" src="https://user-images.githubusercontent.com/123714457/232617242-2fcd5b8f-8d49-4d55-9252-b27c52592ecb.png">
**Note*** Notice we add '--ContentsManager.allow_hidden=True' after the main command to open jupyter lab. This is because the code contains what are known as SDKs, similar to APIs but a little different. To use SDKs we use what are called api/secret api keys, basically like an authentication to be able to access real time financial data, a vital aspect to this protoype application. We store these keys in hidden files (.env), which are otherwise invisible to the human eye unless the additional command defined above is provided when launching jupyter lab. They are originally hidden because keys are like a personal password. BUT, no need to worry about this, I have provided my keys within the code. For more information on APIs/SDKs [Click Here](https://www.bmc.com/blogs/sdk-vs-api/#:~:text=An%20SDK%20provides%20a%20complete,facilitate%20communication%20between%20two%20platforms.)
- **5:** It make take a sec or two for the JupyterLab server to open, but once it does you should have something that looks like this ----> ![Screenshot 2023-04-17 at 3 20 48 PM](https://user-images.githubusercontent.com/123714457/232623126-c7b1d85e-eb55-43ad-851f-c7feed5c5e3c.png)
**Note*** Once you have JupyterLab running, your terminal will look like this and you won't be able to use it. Don't delete it, if you want to use the terminal you can open another new window. The JupyterLab terminal you shouldn't delete will look something like this ----> ![Screenshot 2023-04-17 at 3 22 38 PM](https://user-images.githubusercontent.com/123714457/232623376-803fd2df-c8e0-4849-953f-7f9c9c1350f0.png)

---

## *Usage*

1. You can select the top cell and hit shift+enter on your keyboard to run each cell independently.
2. After selecting the top cell, you can hit the run button near the launcher tab. It looks like a play button for a movie.
3. **I recommend using this way:** 
- With your mouse navigate near the top of the tab, select 'Kernel', then inside Kernel you'll select 'Restart Kernel and Run All Cells...' This will automatically run the whole program for you start to finish. FYI, it may take a few minutes for everything to load!
<img width="400" alt="Screenshot 2023-04-17 at 2 53 35 PM" src="https://user-images.githubusercontent.com/123714457/232619135-6b2f77be-d543-4a59-a4ad-6e62b2113c6c.png">

---

## *Contributor*
For any questions/concerns, anything at all feel free to contact below
- Dylan Johnston
- Email: dylanhjjohnston@gmail.com


---

## *License*

This software is licensed under GNU General Public License v3.0. See the [LICENSE](https://github.com/djohnst914/Loan_Qualifier_New_Feature/blob/main/LICENSE) file for details. 

########################
README
Naoya Ohara, CFA, CAIA
A0197178L
e0395606@u.nus.edu
2021 Sept 13
########################

This whole package of files is the final output for the capstone project of NUS, Master of Computing (General Track). The capstone internship is held at the NUS Fintech Lab.

As a capstone internship of Master of Computing (General Track), NUS, I created a multi agent system (MAS) for crypto-currency trading using case-based reasoning (CBR).

The purpose of creating this system is to offer the body-of-knowledge in algorithmic trading, to show how we can implement MAS and CBR in real world data, and to show how we can utilize the machine learning techniques such as PCA and kNN into real worldÃ¢â‚¬â„¢s financial data, mainly aiming to the learning purpose for the future students and corporate sponsors at FinTech Lab.

This package contains folders and files shown as follows.

*Under the folder NUSFintechLab_Capstone_MAS

-MAS_ALL_Showcase_Final.ipynb
This is the core of the package. This is python notebook file which can run on google colab. It contains whole codes of MAS and explanations of each agent. As this file is the core for the output of the capstone internship this time, you can check this file on google cola first.

-FinTechLab-KC-48269a6c0391.json
This is the json file to run google text analytics when we analyze twitter sentiment. You need to place this file under the folder of NUSFintechLab_Capstone_MAS. When you execute text sentiment analysis, please confirm that you place this file at this folder.

*Folders

-Notebooks_By_Sections
Under this folder, you can find some python notebooks. Those are the part of MAS_ALL_Showcase_Final.ipynb. The purpose of those files is for learning by each topic. For example, you can focus on topics such as "multi threading" and can learn such topics with short simple codes. Also, relevant csv files to learn those materials are saved under this folder.

Note: With regard to the CEO agent, CEO is the orchestrating function of whole agents, such that we can learn only in the context of the whole MAS system. Therefore, there is no individual notebook for CEO agent.

-FinalReport
In this folder, you can find the final report for the capstone project. By reading this final report with MAS_ALL_Showcase_Final.ipynb, you can see the whole picture of the project. Just beyond the "report", I hope that this report can server as a textbook for "the algorithmic trading and quantitative finance with python" and can offer the body-of-knowledge in this area.

Also, all pictures used in the final report are saved under FinalReport -> Pictures. 

-twitter_data
In this folder, the results of twitter sentiment analysis are saved, as it takes long time to crunch (i.e. preprocess, transform, and using fuzzy logic) whole raw data from NUS SQL data library. In the MAS_ALL_Showcase_Final.ipynb, some of those files in this folder is read as pandas data frame and used for the analysis.

-data_sendmail
This folder saves files for the monthly report, the report that RPA agent automatically attaches to email and send.

-backtest_testresult_data
In this folder, the backtest results of train/test split with sliding window are saved. It takes 2-3 hours to complete whole backtest, such that those files are saved under this folder.


Disclaimer
All files and documents are provided for information purposes only to eligible recipients. Any of those files and documents shall not constitute an offer to sell or the solicitation of any offer to buy any interest. The author is not responsible for any loss or damage arising from any investment or any other activities based on any information contained here.
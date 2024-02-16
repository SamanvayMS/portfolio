I'm a graduate student at the University of Illinois, Urbana-Champaign studying quantitative finance specializing in the cutting-edge fields of machine learning, deep learning algorithms, and generative AI. My academic pursuits are firmly rooted in a rigorous exploration of statistics and probability, stochastic calculus, algorithmic trading, high-frequency trading, and quantitative finance. With over four years of hands-on trading experience, I have honed my expertise in point and click strategies, adeptly executing both option writing and tactical strategies across European options in equity, commodity, and currency markets. My engagement with forex CFDs further complements my trading repertoire, underscoring a comprehensive understanding of global financial instruments. I also manage of Portfolio of Long only Equity products. I am continuously engaged in backtesting and the development of novel strategies, leveraging my profound knowledge to architect automated strategy execution systems. These systems are meticulously designed for deployment on the cloud, ensuring scalable, efficient, and effective algorithmic strategy application. Building on this foundation, my experience extends to the proficient use of various deep learning architectures such as LSTMs (Long Short-Term Memory networks), Transformers, RNNs (Recurrent Neural Networks), GRUs (Gated Recurrent Units), and an array of Convolutional Neural Networks (CNNs) And am also in the pursuit of developing features for DQRN Trading Bots that can learn to trade the markets using teh concepts of Q-learning and Reinforcement learning.

## Education						       		
- M.S., Financial Engineering	| The University of Illinois at Urbana-Champaign (_May 2024_)	 			        		
- B.E., Mechanical Engineering | Ramaiah Institute of Technology, Bengaluru (_June 2021_)

## Skills
- **Programming Languages** :- Python, C++, R , SQL, Bash, Git, pinescript
- **Frameworks** :- Docker, Tensorflow, Pytorch, Scikit-Learn, REST-APIs, Quantlib
- **Financial/Trading Systems**:- Bloomberg terminal, TradingView, Metatrader4, RCM-X Strategy Studio, Kite
- **Quantitative Finance**:- Derivatives Pricing, Interest Rate Modelling, Volatility Surfaces, Portfolio Optimisation, Options Strategies

## Work Experience

**Summer Internship @ JIA Finance (_June 2023 - Aug 2023_)**
- Developed an automated system using OpenAI API, LangChain, and FAISS/Chroma db for interpreting mortgage guidelines, facilitating rapid validation of loan requirements using Retrieval Augmented Generation (RAG).
- Engineered task-specific QnA chains and enhanced query handling with a Recursive Tree Approach and LLM-based memoization, improving response accuracy to complex mortgage-related inquiries to 80% (from 55% for direct queries).
  
**Student Practicum @ JIA Finance (_Jan 2023 - May 2023_)**
- Utilized AWS Sagemaker and Redshift Connector for EDA on over 100M Fannie Mae mortgage records, applying data manipulation and visualization tools for insights.
- Modeled loan survival and default rates curves, employing the Cox Proportional Hazard Model and Kaplan Meier Filter and assessing the impact of macroeconomic factors.
- Crafted a comprehensive cash flow model for Mortgage Backed Securities (MBS) integrating credit default, prepayment, and loss severity with a Cox Ingersoll Ross (CIR) interest rate model.

**Student Practicum @ bp Trading (_Aug 2023 - Dec 2023_)**
- Architected forex tick data Procurement and Preprocessing pipeline to efficiently proces and convert tick level Forex Bid Ask Quotes to OHLC data
- Developed a Forex ladder trading strategy focusing on grid and lot sizing optimizations to enhance return potential using quantitative methods.
- Sped up tick level backtest up to 2000x using Just-In-Time Compilation on various major currency pairs.
- Applied hyperparameter tunin, trying carious automated techniques such as Optuna, PySwarm, DEAP (Genetic Algorithms) and utilized strategy validation techniques such as Walk-Forward Analysis and Monte Carlo simulations, to refine proprietary trading models.
[link to repository](https://gitlab-beta.engr.illinois.edu/fin556_algo_market_micro_fall_2023/fin556_algo_fall_2023_group_01/group_01_project)

**Trader - Self Funded (_Aug 2020 - Present_)**
- Built custom libraries for Historical Data Procurement, live tick and L2 orderbook data streaming and warehousing using popular broker APIs
- Architected custom modules to backtest strategies on historical data and to simulate real-time paper trading with brokerage and slippage analysis with capability to shift to live trading on Google Cloud Platform.

## Projects
### High Frequency Trading and Market Making
- Carried out extensive analysis of Level 2 Order Book and Market By Order (MBO) data from IEX, Nasdaq's ITCH, and CME Globex datasets in python.
- built pipelines to procure and parse MBO data for conducting nanosecond-level backtesting on RCMX's Studio Studio platform.
- Designed and implemented various mean reverting and trend following market-making strategies with Dynamic programming and inventory control for optimal bid-ask placement in C++.
- Built complete backtesting pipelines in bash for parameter optimisation and results and processing.
- Experimented with Transformers and LSTMs built with Pytorch.
[link to repository](https://gitlab-beta.engr.illinois.edu/fin556_algo_market_micro_fall_2023/fin556_algo_fall_2023_group_01/group_01_project)

### Trading Strategy Development and Implementation
- Evaluated and integrated technical trend indicators like VWAP, EMA, and momentum metrics ADX and DI to formulate advanced trading strategies.
- Enhanced strategies with rigorous hypothesis testing, GARCH (1,1) model analysis, and Volume Weighted Average Price application.
- Applied hyper-parameter tuning and Monte-Carlo simulations to refine models and mitigate overfitting.
- Conducted a comprehensive literature review to ground strategy improvements in academic research.
[link to repository](https://gitlab-beta.engr.illinois.edu/fin556_algo_market_micro_fall_2023/fin556_algo_fall_2023_group_01/group_01_project)

### DQN Forex trading Agent
- Designed Custom OpenAI Gymnasium Environments To train Deep Q network(DQN) models.
- Experimented with various DQN and Deep Q Recurrent Network models with custom residual blocks for efficient action masking and dynamic Inventory control.
- Generated Alpha of atleast 108 percent yearly over Simple Buy and Hold returns on Forex products after accounting for spread and execution costs with minimal drawdowns which could be scaled up further utilising leverage.
- Currently In Process of Hyper Parameter Optimisation and Paper Trading tests before Live Deployment using Oanda's API.

### DQN Equity and Futures Market Making Agent (Independent Study Under [Professor David Lariviere](https://www.linkedin.com/in/davidlariviere/))
- Utilized Pipeline from previous Market Making Project to procure Data from CME's Globex Dataset for Futures MBO data and Nasdaq's Itch Dataset for Equity MBO data.
- Constructed a DRQN with Complete control over inventory and spreads and designed proprietery rewards scheme to penalise model when it exceeds inventory limits and doesn't adhere to market making conditions. 
- Built custom Backtesting and learning pipeline for training DQNs using Strategy Studio's Backtesting Engine to generate experience replays from MBO data for randomly sampled dates.

### Trading with Kite Trade Api
- Architected Modules for Live and Paper Trading on Indian market using Kite Trade API
- Modules to systematically handle multiple trading strategies simultaneously and manage portfolios of individual trading agents.
- Automate Login and access token generation using webdriver, chromedriver and beautiful soup for seamless strategy execution.
- Built safety mechanisms and kill switches for shutting down trading agents during high drawdown situations. 

### Variational AutoEncoders for Financial Feature Space Decomposition.
- Experimented with Using Variational AutoEncoders to reduce High Dimensional Time Series Data consisting of widely used Technical Indicators with multiple lookback periods.
- Converted features into images to feed into CNN based encoder decoder model.

### LSTM based Option Pricing Models.
- Trained LSTM models on Time Series Data with proprietary features to exploit market fractals and project asset paths for improved Montecarlo Simulations for Valuing Vanilla and Exotic Options.
- Constructed models to project 95 percent confidence interval ranges for assests to execute straddle and strangle option strategies.

### Aerodynamic development of a Formula SAE Race car
- Simulated various Airfoil profiles and angle of attack to arrive at the optimal parameters for the Aero package to maximise downforce(negative lift) and minimise drag using Ansys Fluent for airflow simulations.
- Ran height and depth Optimisations for the venturi tunnels to optimise inlet and diffuser height.
- Designed and constructed the Rear Wing, FRont wing and Underbody diffuser package for a model formula student vehicle in DS Solidworks adhering to the FSAE rulebook.
- Ran in-depth 3D CFD(Computational Fluid Dynamics) simulations of the vehicle with and without the Aerodynamic Package attached and under various road conditions in Ansys Fluent.
- Conducted indepth study of drag and downforce parameters with a comprehensive visual study to analyse the airflow around the car and the wake behind the car.
- Conducted Track simulations on various FSAE Tracks to verify improvements of proposed package and correlate with performance improvements observed in CFD simulations.

## [Certifications](https://www.linkedin.com/in/samanvay-malapally-sudhakara-148836212/details/certifications/)
- **Bloomberg market concepts**:- Equities, Commodities, Fixed income, Portfolio Management, Economic indicators, Terminal Basics
- **Deep Learning Specialisation**:- Deep Neural Networks, Sequence Models, Convolutional Neural Networks, Machine Learnng Planning, Hyperparameter Tuning and Optimisation.
- **Machine Learning Specialisation**:-Supervised Machine learning (Regression and Classification), Boosting and Ensemble Learning Algorithms, Unsupervised Machine Learning, Reinforcement Learning.

## Other Links
- [Linkedin](https://www.linkedin.com/in/samanvay-malapally-sudhakara-148836212/)
- [Data Science Blog](https://medium.com/@samanvayms99)


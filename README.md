Hello World!
This repo is to accomplish the followings using Python and Google Colab:
- fetch data from the coinbase API https://docs.cloud.coinbase.com/exchange/reference/exchangerestapi_getproductcandles
- calculate a 200-day (window size is customizable) Volume-Weighted Average Price VWAP for cropto pairs (such as BTC-USD, ETH-USD and ETH-BTC)
- unit tests on the code

URLs:
working Google colab script(public): 
https://colab.research.google.com/drive/1Likrf-6EGEpNcRKJb5Q0VB83xmEjeivg?usp=sharing
Repo(public): 
https://github.com/YaokunLin/coinBaseVwap/blob/main/VWMP.ipynb

Scratch Work for testing with visulization(public): 
https://colab.research.google.com/drive/13Ib-YSgfSOESpoAYbrZuaSNwTtjt4V__?usp=sharing
Repo(public): 
https://github.com/YaokunLin/coinBaseVwap/blob/main/VWMP_ScratchWork_forTesting.ipynb

main object implementation and design:

![image](https://user-images.githubusercontent.com/72329369/141181083-5531b2fb-d231-444d-843e-43356b24523c.png)
![image](https://user-images.githubusercontent.com/72329369/141181800-4dad01ec-fe60-4c23-b843-55b925fcea51.png)
![image](https://user-images.githubusercontent.com/72329369/141181173-8a91d712-ce87-4aab-a984-759d47066a92.png)

Working Example:

![image](https://user-images.githubusercontent.com/72329369/141181876-2c6ad9d1-4a12-4ca3-a391-5e6c4bc2dea7.png)

Unit tests Implementation:

![image](https://user-images.githubusercontent.com/72329369/141181946-fab7e037-6519-4c6b-92d6-bbf20c121ef8.png)
![image](https://user-images.githubusercontent.com/72329369/141181977-78d62148-642a-4ca1-9c2c-cae4b485c0c0.png)
![image](https://user-images.githubusercontent.com/72329369/141181996-03db0658-6ff0-4285-93ab-4573a427046e.png)

Test Results:
![image](https://user-images.githubusercontent.com/72329369/141182027-b1da2083-e1ce-46b7-b17d-a235a55aa2e3.png)

ScratchWork and Visulization:

![image](https://user-images.githubusercontent.com/72329369/141182227-82eb0413-da75-4c6b-9095-58ea6a3a4062.png)



# Load_PV_Prediction_Using_XAi

The project aims to predict electricity generation and load per hour in Toronto using **LSTM** Recurrent neural networks.
**XAI (eXplainable AI)**, a machine learning library designed with AI explanation potential as the core, is also used. XAI was used for analysis and evaluation of data and models, and SHAP (SHapley Additive exPlanations) was used among XAI models.

# Dataset

> The dataset is the hourly power consumption in Toronto, which can be downloaded from :
[https://www.torontohydro.com/SITES/ELECTRICSYSTEM/BUSINESS/YOURBILLOVERVIEW/NETSYSTEMLOADSHAPE/Pages/default.aspx](https://www.torontohydro.com/SITES/ELECTRICSYSTEM/BUSINESS/YOURBILLOVERVIEW/NETSYSTEMLOADSHAPE/Pages/default.aspx)

> The weather dataset is the hourly weather data in Toronto, which can be downloaded from :
https://climate.weather.gc.ca/historical_data/search_historic_data_stations_e.html?searchType=stnProv&timeframe=1&lstProvince=ON&optLimit=yearRange&StartYear=2016&EndYear=2017&Year=2022&Month=5&Day=26&selRowPerPage=25&txtCentralLatMin=0&txtCentralLatSec=0&txtCentralLongMin=0&txtCentralLongSec=0&startRow=76


# Results


### Power Generation Prediction Results :

![](https://lh3.googleusercontent.com/J_FxPVryMC1YvH7Izo5B231K0JrfpTe2Cd9BK5YMgKynlL7O1nU9582g28aBeP0nPKz1TbAt1B-w0NvkY_Xq2CZ4CgQPNLMULRbqGAuhpdtBThQMvIoDx6w-6uP9YGJUrnSjpATj0WJ6R8hdBeiVobbEyj4BS1BrirD7zfottYMRpzvY6fCUcsIzkLSb-zVxrHUwsTTiTQiun219RVUNrWMpWv1Jo--ing_GQ2gdsgNly7An4e21Ix3qquFexfv-ZPhM50XtA_zgRLcYJ8wThRWQUwPFIMWRznwCYSaEM4U2qqlhmWXlL-wCSJWxULCZ6zONq1dNGmAQ9celGxL4Pk0RCXrODwHFxehmFqXKGdBZggmi3Uozj4PEhoNHo_8aJuFmUEb3KRh0iV2-S2l1-Ra-wQb-9WFBCpRq7dS95FitC7wAvzurJ1kEJiXK9eYoh1DsNmsndrwDJBuhcypApw-6pgbO7ENBd-6fB-KD41EPV2mq4xKx2kGbqSQoRhG-0a47rqIanx9XG4XcQie3M9A6kaJ1BxJ0dOisuFiPisoHCT1l4VcE0e1lziVK1Jt9VKpNBIXbmyeOQrtReNbw4AEVa1IIZF6COuMxkmw9Sd14RCOsgo9n-QUn9emWKft-iviUhJHWK5ACDsl57twj4Wcv7QBx9_bCz02U3jWPP22Jf1UTSCmcvTS0qnIUxqzdpj7MbCItPXVViuENNVaoG5Pqfik16vHAmrN0qsfL2TWLCa46vYmtETaDLUQ=w1725-h371-no?authuser=0)

### Load Prediction Results :

![](https://lh3.googleusercontent.com/2lvey2q8Ly6Z95b1O4TijB4hDvfXrG57bm5TUYoLH54oXRqBNs6-4OaWIzS4Vf9qlUKFOp5lsaoORB8Lfq3Z3mmSmHmJXzq5vm_MRdUs8_TZhv-9B1aFdootvj4QBgG1qBGeOKBIZyiGOjjLnXO67xkRVGX0wiplZiRWVTvBaBaeGVnHCXv264FRw0RiEsbEXqwxVjKL7vT6fw9VIOKe-QjT5ofCl0ndaYbV2_PaTFBvx8Uzq_IW0418iGQrSw8k47pfNkrUuuqPN_FI0HCJHaQjU5ikGDw9mLdSOZrAKB3bACffAx7FQdRFEmCIsDg2pz7ImOw5KoKRvXZXgONrfKI9o5j8Rf9zVToiGmqGlEKVQPjJaoKn-vkQ4klGd13odzipblcmbPhXHWlj2KtaPNqji6FW70fgahaieCUQIUche-dTUp2XwK42-hRsrU7kCkHmUcjx-3w-jbSFAbEAk-utIYmzEF_2xKUk2-5wQCw1VA8zQOMyeX-5fGKlucYNnK-KrtGhwgYSD8sTQxK9v5yKPHATuxABKPAK6nBaplXcPum99R_AX9o4gJsKncKrYpPCB8CLQIykF03RhDHUJMo7oIGBvVUEU4JAw0M6o7p2dMv4bVGlX3msWRTvtfnCAqNM24josTlpbvwmK0OH4a0b246gMILxJHB4KIQhmbivnhDA-FisbTkOewuvC-BFUADp7bAp9SY4Xgi0kjbvijoqcyFTogadZHuBIQEhLvkFjGR6nkt184TgrEY=w1836-h371-no?authuser=0)

# OTT-analysis--First-Show-after-buying-a-subscription---SQL

Problem - To find out which show the person watched first after buying an OTT’s subscription plan.

![1](https://user-images.githubusercontent.com/91282080/139040714-02f140c5-43a1-475e-a918-4c2b238b59af.jpg)

![2](https://user-images.githubusercontent.com/91282080/139040731-839e4203-775e-4982-afd6-0132a738abfc.jpg)

Solution – We have used lag to find out what the first entry is on the basis of username for the person after they have bought the subscription.
We created a new variable called 1st_show, we denoted the value of 1 against it, when it was the first entry for a distinct user_id after purchasing the subscription.
Then we recalled our final solution by asking SQL to return, the show column as first show and user_id where the 1st_show variable had the value of 1.
Hence, we get our desired result.

![3](https://user-images.githubusercontent.com/91282080/139040819-cf394208-0c7e-4f7e-adba-7e32e5a8ad96.jpg)

## *Problem Description:*
    
#### *XYZ operates over 3,000 drug stores in 7 countries. XYZ store managers are currently tasked with predicting their daily sales up to six weeks in advance.
 Store sales are influenced by many factors, including promotions, competition, school, and state holidays, seasonality, and locality. With thousands of 
individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied.*

#### *You are provided with historical sales data for 1,115 XYZ stores. The task is to forecast the "Sales" column for the test set. Note that some stores in
 the dataset were temporarily closed for refurbishment.*


### <u>Data fields:</u>

* **Id** - An Id that represents a (Store, Date) tuple within the set
*  **Store** - A unique Id for each store
*  **Sales** - The turnover for any given day (Dependent Variable)
* **Customers** - The number of customers on a given day
* **Open** - An indicator for whether the store was open: 0 = closed, 1 = open
* **StateHoliday** - Indicates a state holiday. Normally all stores, with few exceptions, are closed on state holidays. All schools are closed on public holidays and weekends. a = public holiday, b = Easter holiday, c = Christmas, 0 = None
* **SchoolHoliday** - Indicates if the (Store, Date) was affected by the closure of public schools
* **StoreType** - Differentiates between 4 different store models: a, b, c, d
* **Assortment** - Describes an assortment level: a = basic, b = extra, c = extended. An assortment strategy in retailing involves the number and type of products that stores display for purchase by consumers.
* **CompetitionDistance** - Distance in meters to the nearest competitor store
* **CompetitionOpenSince [Month/Year]** - Gives the approximate year and month of the time the nearest competitor was opened
* **Promo** - Indicates whether a store is running a promo on that day
* **Promo2** - Promo2 is a continuing and consecutive promotion for some stores: 0 = store is not participating, 1 = store is participating
* **Promo2Since [Year/Week]** - Describes the year and calendar week when the store started participating in Promo2
* **PromoInterval** - Describes the consecutive intervals Promo2 is started, naming the months the promotion is started anew. E.g. "Feb,May,Aug,Nov" means each round starts in February, May, August, November of any given year for that store
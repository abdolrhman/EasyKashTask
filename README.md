# EasyKashTask

Get Seller Transactions
---------
- Description:
    - should return transaction listing for the logged in seller (use seller id as param to avoid the need to implementing auth module).
- URL: `{{url}}/transaction?page=1&per_page=10&seller_id=id`
- Type: `GET`
- Headers: `Token: ABC`
- Request Params: `page, per_page, seller_id=id, 
- Response Schema:
```
{
    data: {
      transaction: [
        {
            id,
            title,
            fees,
            amount,
            last_updated,
        },
      ],
      paging: {
        total: 20,
        current_page: 1,
        per_page: 10
      }
    }
}
```
- Entities: `Seller, Offer`
 -Please create  Simple angular app which will fetch The End point (As a tabel with paging )
- Please use TypeScript, Mysql, Sequelize and Express to impelement this endpoint.
- Please use small git commits (Not just one Large [initial commit]).
- Please put this on a private git Repo with steps to run in a `README` file and send an invitation to us And make a pr on `review` branch 
 *** Bounce
- add unit tests (Mocha preferd )
- add one integration test For this endpoint 

------------------------
This task is just to test your abilities with the given technologies,
Good luck

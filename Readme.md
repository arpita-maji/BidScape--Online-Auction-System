# BidScape - Online Auction System

BidScape is an online auction system. It is a web-based platform that facilitates the buying and selling of goods and products through an auction format. It provides a virtual marketplace where individuals or businesses can bid on items, and the highest bidder wins the item being auctioned. The website also cntains tendering feature. Tenders are commonly used in public procurement processes by a company, organization, or government agency for suppliers or contractors to submit competitive bids to supply goods or products, and the lowest bidder wins the item being auctioned. The online auction system offers a convenient and efficient way for sellers to reach a large number of potential buyers and for buyers to access a wide range of products and services. It eliminates geographical limitations and allows participants from different locations to engage in bidding activities.

## Features

- A user interface for users to register.
- The seller is able to create an auction for selling a product or service with an expiry timeline.
- Sellers can select the type of bidding, either auction or tender.
- The seller can select categories for the products, such as mobiles, automobiles, real estate, electronics, etc., that will be put up for auction.
- Bidders can bid in increasing order.
- The bidder can post queries for the product on the posted auction, and the seller should be able to answer questions.
- No bids for the same amount will be accepted. 
- For auctions, when the timeline expires, the highest bidder wins the item being auctioned, and the order will be placed.
- For tenders, when the timeline expires, the lowest bidder wins the item being auctioned, and the order will be placed.
- If no bids are received even after the timeline expires, the status changes to not sold. 
- Once the timeline expires, no bids will be accepted. 
- A leaderboard to showcase the winners of the auction.

## Technologies Used

### Frontend:
- HTML
- CSS
- Bootstrap 
- JavaScript

### Backend:
- Python
- Django
- SQLite

## Getting Started

### Prerequisites

```bash
asgiref==3.6.0
backports.zoneinfo==0.2.1
Django==4.2.1
python-dateutil==2.8.2
pytz==2023.3
six==1.16.0
sqlparse==0.4.4
tzdata==2023.3
```
Or

Install the above required packages using:

```bash
pip install -r requirements.txt
```
### Deployment

To deploy this project run:

```bash
python manage.py runserver
```
Open your browser and browse to the following address:

```bash
http://localhost:8000/
```
## Screenshots

![Screenshot 2023-06-14 010802](https://github.com/arpita-maji/BidScape--Online-Auction-System/assets/119843428/39957607-2c7c-4ab2-b173-89429c76eb2c)

![Screenshot 2023-06-14 010233](https://github.com/arpita-maji/BidScape--Online-Auction-System/assets/119843428/4d86479b-4442-469a-a890-bbef68c27b85)

![Screenshot 2023-06-14 010409](https://github.com/arpita-maji/BidScape--Online-Auction-System/assets/119843428/f3849901-e298-43be-bbfd-7fcd0550275c)

![Screenshot 2023-06-10 215621](https://github.com/arpita-maji/BidScape--Online-Auction-System/assets/119843428/237b3dbe-1924-421f-8f77-6b6e4ea8f2f2)

![Screenshot 2023-06-10 220115](https://github.com/arpita-maji/BidScape--Online-Auction-System/assets/119843428/c0a309b4-792d-4bfa-b510-a4fbeb96dcbc)

![Screenshot 2023-06-10 221357](https://github.com/arpita-maji/BidScape--Online-Auction-System/assets/119843428/9d2fddb9-4684-4e4e-adf8-65fe401341c3)

![Screenshot 2023-06-10 221155](https://github.com/arpita-maji/BidScape--Online-Auction-System/assets/119843428/287c7cfe-de24-4819-a303-ab05a02c3321)

![Screenshot 2023-06-10 220538](https://github.com/arpita-maji/BidScape--Online-Auction-System/assets/119843428/f366aca5-33ee-422b-a5ef-07c03b1f886a)

## License

[MIT License](https://github.com/arpita-maji/BidScape--Online-Auction-System/blob/master/LICENSE)
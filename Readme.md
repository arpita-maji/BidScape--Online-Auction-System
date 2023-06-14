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

![image](https://github.com/arpita-maji/BidScape--Online-Auction-System/assets/119843428/1970bd9f-81e9-40e2-8ea4-52fd88683182)

![image](https://github.com/arpita-maji/BidScape--Online-Auction-System/assets/119843428/89e0a4a4-318c-4e0c-8f92-66491ebca10d)

![image](https://github.com/arpita-maji/BidScape--Online-Auction-System/assets/119843428/136b13a1-ddcb-42af-b6e6-db740cdf7883)

![image](https://github.com/arpita-maji/BidScape--Online-Auction-System/assets/119843428/07c498ca-acb7-4dd1-ac1b-4f177f2cd391)

![image](https://github.com/arpita-maji/BidScape--Online-Auction-System/assets/119843428/02372378-8597-444a-8c24-a3e17f923739)

![image](https://github.com/arpita-maji/BidScape--Online-Auction-System/assets/119843428/f39d0ddd-122b-41b1-aed5-afa81eb076ae)

![image](https://github.com/arpita-maji/BidScape--Online-Auction-System/assets/119843428/025a474e-8b9f-49ef-9499-de7fa00b5693)

![image](https://github.com/arpita-maji/BidScape--Online-Auction-System/assets/119843428/381678be-3c5e-4346-80c7-edbd5bfcf10e)

![Screenshot 2023-06-10 220538](https://github.com/arpita-maji/BidScape--Online-Auction-System/assets/119843428/befbf618-05f6-4ee0-8dd6-d1b4a8a4a020)

## License

[MIT License](https://github.com/arpita-maji/BidScape--Online-Auction-System/blob/master/LICENSE)
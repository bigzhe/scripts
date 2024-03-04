I want you to help me record my daily expenses. I will provide you with the purchase details, and you can help me to extract the expense, the retailer, the date and time, and the amount, 
and predict the category of the expense. The amount should be the prefixed with CHF.

Following is the purchase details, and you can help me to extract the expense and predict the category of the expense. The amount should be the prefixed with CHF. 

I have the following categories: 
- Groceries: some of my often-go-to grocery stores are Migros, Coop, Aldi, Lidl, Denner, Spar, Maxim Food, Muller, Lian Hua, Aligro, Shahin Aria
- Restaurant: I often go to McDonald's, Burger King, KFC, Subway, Starbucks, and other local restaurants. I have lunch at UZH Mensa, named "UZH Binzmühle".
- Housing: Rent or mortgage payments, property taxes, homeowners or renters insurance, maintenance, utilities (electricity, water, gas), and household supplies. My renter is Allianz Suisse. My electricity provider is EKZ. My internet provider is Sunrise (Yallo).
- Transportation: Car payments, fuel, maintenance and repairs, public transportation fares, parking fees, tolls, and vehicle insurance. I often use the following services: SBB, ZVV, Uber, and Mobility.
- Healthcare: Health insurance premiums, co-pays, prescription medications, over-the-counter medications, and medical supplies. My health insurance is from Helsana and Sanitas.
- Utilities: Phone bills, internet, cable or streaming services, and subscriptions.
- Debt Payments: Credit card payments, student loans, personal loans, and any other debts.
- Insurance: Life insurance, disability insurance, long-term care insurance, and other types of insurance premiums. Health insurance is not included here.
- Personal Care: Haircuts, salon services, grooming products, and cosmetics.
- Electronic Devices: Phones, computers, monitors, etc. I often shop at the following stores: Digitec, Interdiscount, Microspot, Melectronics, MediaMarkt, Fust, and Brack.
- Home Appliances: Things that will be used by the family, like cookers, cleaning devices, etc. I often shop at the following stores: Galaxus, Amazon, Ikea, Conforama, and Jumbo.
- Entertainment: Movie tickets, concerts, sporting events, hobbies, streaming services, books, magazines, PS5 games, and other games.
- Clothing and Accessories: Clothing purchases, shoes, accessories, and dry cleaning expenses. I often shop at the following stores: BestSecret, Zalando, H&M, C&A, and PKZ.
- Education: Tuition fees, textbooks, school supplies, and educational materials.
- Savings and Investments: Contributions to savings accounts, retirement accounts (e.g., 401(k), IRA), and other investments.
- Gifts and Donations: Gifts for friends and family, charitable donations, and contributions to crowdfunding campaigns.
- Travel: Airfare, accommodation, transportation, meals, and other expenses related to vacations or trips.

I want you to return me for each expense the amount and the category. I want the amount to be in the format without the currency symbol and with the thousands separator ' and ,. For example, CHF 1'000.00 should be 1000.00. If you think the provided details are not for an expense, e.g., wrong message sent by accident, you can set confidence to 0. I want the date and time to be in the RFC 2822 format, e.g., "Fri, 01 Mar 2024 17:07:00 +0100".


I want the answer to be in the following format:
Amount: [Amount]
Retailer: [Retailer]
DateTime: [DateTime]
Category: [Category]
Confidence: [Confidence Level]%

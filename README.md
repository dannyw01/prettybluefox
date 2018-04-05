# prettybluefox
Description of and arguments for my Reflector project

I want to make a huge improvement in users' security and privacy on the internet. I call the proposal 'Reflector'.

Instead of companies storing user data on their own servers, I want users to store their own data on a server where the user pays for the service and the company providing the service has no income from any of the organizations which the user may allow to access that data. Call the company that stores the data for the user 'Festung' and the company which creates and accesses the data 'Fishy'. And call the user 'Fred'.

The user can send a company like Fishy permission, ie perhaps an encoded version of Fishy's public key, to access certain data. Fishy can then read certain records and fields, and write certain records and fields, as long as Fishy complies with the user's rules (which Festung enforces) and the user wishes to continue.

Fishy pledges to keep the Fred's data only in temporary storage. It is not easy to verify such a pledge, but it seems much easier to me to verify that Fishy is not routinely handling stored data than making sure that no copies are ever made of the data in a database. For instance, credit card companies have already been fairly successful in preventing companies like Fishy from storing full credit card data.

At present a company like Fishy does a lot of database accesses which would be very clumsy using Reflector, like 'select all users in Manchester who bought a book last month'. I happen to think that many such accesses like tend to be made for the benefit of Fishy, not Fred.

Fishy is allowed to retain data which is created and used by Fishy itself, like the product ordered, the price, the ship date, the call operator, etc. But this data links only to the customer id, and Fred is the only one who knows his id, and Fishy only remembers the id, not Fred.

For payments, there would need to be some sort of trust relationship between Fred and a sort of bank (called 'Bulgy'), and a trust relationship between Bulgy and Fishy. The details of the transaction could be handled with two-way anonymity, although existing legislation on banking would prevent that.

Clearly Festung would be an attractive target for hackers. On the other hand, all of its communications can be encrypted, and all of the data it holds might be held in a form which can be decrypted only by Fred and Fishy. Also, Fred only needs a single secure connection, so he can put the maximum effort into operational security with Festung, instead of having to spread his efforts across dozens or hundreds of sites. And Fishy can update its security processes just with Festung and similar companies, instead of waiting for all the people like Fred to upgrade before Fishy can fix weaknesses.

It would take millions of dollars and hundreds of people to start this project. I hope I can at least get Reflector discussed, so that people see that we don't just have to trust every company we deal with to handle our data responsibly for ever.

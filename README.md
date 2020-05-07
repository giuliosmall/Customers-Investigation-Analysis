# customers_investigation
Project created to explore and investigate the possibility for a traditional cosmetic company to enter the "green" sector

## INTRODUCTION
Beautiful is a company selling cosmetics, mainly in the UK. The company have been providing fragrances, skin care, and makeup since the nineties and has now decided to enter in the green marketing and widen their offer through a line of natural products. The main issues marketing managers want to understand, before proceeding with a particular strategy regard:
- The differences in attitudes and characteristics between consumers/non-consumers of natural products (today non-consumers can be tomorrow customers?)
- the factors impacting on the willingness to buy, and on the purchase habits
- the products to which customers are more interested
- the product characteristics on which customers focus their attention
- the way customers form their information about the products
- the existence of particular dimensions along which consumers of cosmetics perceive natural products
- the existence of particular profiles of customers, in terms of lifestyle, perceptions, sociodemographic characteristics
To understand the attitudes of prospect customers, they develop a questionnaire to investigate the most important factors influencing customers’ choices and preferences, as well as a number of variables related to lifestyle, purchase and use habits, and a small number of sociodemographic variables. The questionnaire was administered through the CAWI (Computer Assisted Web Interviewing) technique, with recruitment through social networks (snow-ball sampling). The questionnaire was administrated to 209 respondents, obtaining 138 valid questionnaires. To facilitate respondents, the questionnaire was articulated in several sections:
1. Natural cosmetics The first section of the questionnaire was aimed at collecting general information on the perception of natural cosmetics and on the propensity to purchase the category by the respondents, in order to have a first classification of purchasers of natural cosmetics. In particular, the attitude of the latter has been examined with reference to the categories of products purchased, the frequency of shopping and the methods for finding out the characteristics of the products.
2. Facial care products The second section was aimed at detecting information regarding the purchase behaviour of facial care products, including a series of aspects such as, for example, distribution channels and relevant product attributes. This part was oriented to the evaluation of the variables concerning the entire process of purchase of skincare products by the interviewees, regardless of their propensity, in terms of purchase / non-purchase, towards natural cosmetics.
3. Face Care A section dedicated to the theme of “face care” was introduced, to understand what were the habits and styles of consumption of the respondents compared to the category investigated. For example, it was asked to indicate the type of product most purchased (hydrating, purifying, etc.), also assessing the level of interest and involvement of consumers for the beauty world.
4. Lifestyle Another section was dedicated to lifestyles, submitting to the assessment of the participants a series of statements about different topics such as nutrition, personal care, environmental sustainability and leisure time.
1
5. Personal Information Finally, the last part has been designated to collect the personal data of the respondents, such as sex, age, educational level and employment status.
ROADMAP:
1. Create an index summarizing the attitude towards natural cosmetics (V18-V26)
2. On the index, regress sociodemographic variables (V94-V97) to check if they have an impact
3. Add variables regarding the way they obtain information (V11-V17)
4. Factor analysis on general lifestyle questions (general: V70-V85, spending: V86-V93)
5. Cluster based on relevant factors found
• – Add factors found to multiple regression model and check which ones have an impact
6. Profile them by looking at sociodemographic variables in each cluster
7. Further profiling using cross tabulation to look at attitude towards natural products, willingness to buy (V3, V4).
8. Logistic regression on willingness to buy to check if it depends on the distribution channels people choose (face care) and the way they retrieve information before they buy (face care)
• – Interest in product categories (V5-V10)
9. Definition of natural products to understand how to market a new product, what to highlight
First of all, seeing as there were some missing values in the dataset, we remove the rows containing them and create a secondary dataset with them. This could potentially be used to look into people who did not respond to specific questions.

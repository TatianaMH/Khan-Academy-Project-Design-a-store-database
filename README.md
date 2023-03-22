# Khan-Academy-Project-Design-a-store-database
Khan Academy wants me to design a store so I am taking inspiration and stock from my own small business website and will be writing it in this project.

**This is the SQL I typed myself**

[Link to acutal project](https://www.khanacademy.org/computer-programming/spin-off-of-project-design-a-store-database/5440787262521344)


CREATE TABLE crochet (id INTEGER, name TEXT, colors
TEXT, location TEXT, price NUMERIC);

INSERT INTO crochet VALUES (1, "Fjord Horse", "Cream, Beige, Grey, Black.", "Suitcase", 23.35);
INSERT into crochet VALUES (2, "Crochet Infinity Scarf" "Light Purple.", "Suitcase", 23.35);
INSERT into crochet VALUES (3, "Skeleton Dragon", "Grey , White, Black.", "Suitcase", 33.35);
INSERT into crochet VALUES (4, "Giant Pug", "Beige, Black, White.", "Beside Dresser", 53.35);
INSERT into crochet VALUES (5, "Yellow Patternless Crested Gecko", "Yellow, Beuge, Black.", "Suitcase", 18.35);
INSERT into crochet VALUES (6, "Big Espeon Inspired Plush". "Light Purple, Dark Purple, Red.", "Suitcase", 28.35);
INSERT into crochet VALUES (7, "Betta Fish In a Jar", "Blue, Black", "Desk", 18.35);
INSERT into crochet VALUES (8, "Butterfly in a Jar","Green, Black.", "Desk", 18.35);
INSERT into crochet VALUES (9, "Gypsy Vest", "Grey", "Suitcase", 38.35);
INSERT into crochet VALUES (10, "Pikachu Inspired Scoodie" "Yellow, Black.", "Suitcase", 33.35);
INSERT into crochet VALUES (11, "Arm Knitted Infinity Scarf", "Blue, Black. Blue", "Back Of Bag", 13.35);
INSERT into crochet VALUES (12, "Ruffle Scarf", "Multi-colored", "Garbage Bag in Suitcase", 13.35);
INSERT into crochet VALUES (13, "Cover up", "Silver-White Multi-colored", "Suitcase", 33.35);
INSERT into crochet VALUES (14, "Giant Crochet Doily", "White", "Suitcase", 33.35);
INSERT into crochet VALUES (15, "Bookmark Crosses", "Pink. Silver. Purple. Blue", "Suitcase", 6.35);

SELECT * FROM crochet ORDER BY price);

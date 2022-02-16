# WildCo-to-SPI

This code is meant to take output data from the WildCAM database and reformat it to fit into the BC SPI Wildlife Camera template.

This code assumes:
  1. Juveniles are always of an unknown sex
  2. No sub-adult and yearling data is taken
  3. Sex classifications in 'Adult + Juvenile' images only refer to the adults (because juveniles are always of an unknown sex)
  4. In events with more individuals than the number of classifications (e.g. Mixed adults, 6 in group), specific group composition is noted in the comments using the following format (without quotes):
    "x males, y females, z juveniles"
    Unused words can be omitted, the order can be changed, and each word can be singular (e.g. "3 females, 1 juvenile" would work as well)
    
Please feel free to contact me at tristen.brush@gov.bc.ca with any questions or revisions. I am new to R and GitHub, and I am eager to learn more!

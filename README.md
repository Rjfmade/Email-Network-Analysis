# Email Network Analysis
 
    Disclaimer: This is an ongoing project I still need to explain the key indicators and the representations, probably comparing them with ramdom graphs. 
    I had publish this code as an exemplification of other projects i am imvolved. However, I do not have the permission nor the authority to make them public.

    This is a quick overview of a Network by extracting the key parameters to understand its strucutre.

The used dataset comes from --> Guimera, R, Danon, L, Diaz-Guilera, A, Giralt, F, Arenas, A. Phys. Rev. E 68 , art. no. 065103 (2003).

The edge list represent the mails sent in a company between 2 people represented by numbers.

## Structure

data/
    initial --> We find the intitial edge list
    output --> we could find the excel file with the main stats extracted from the network

image/
    here we could find the different representations to better understand the data

jupyter-notebook/
    Email_Network_and_Stats --> We create the Graph and extract the main stats. As network processing involves intensive use of resources we will only have to do this process once. If we had more nodes and edges the processing power for retrieving stats like the RandomWalk increase exponentially.

    Email_Network_Visualization --> I have just created this two png files because the network was little enough to do so and it is kind of cool

    Email_Data_Visualization --> Here, once we had retrieved the data from the network in an excel file, we will start playing with it in order to achieve a better understanding of the structure of the network.


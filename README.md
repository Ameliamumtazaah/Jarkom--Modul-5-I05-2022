# Jarkom-Modul-5-I05-2022
| Name | NRP |
| ------ | ------ |
| Amelia Mumtazah Karimah | 5025201128 |
| Shafina Chaerunisa | 5025201129 |
| Muhammad Fadli Azhar | 5025201157 |

``` PREFIX IP Group = 192.209```

## List of problem
1. Create a network topology according to the design provided by Loid
2. Make the topology using the CIDR or VLSM technique after subnetting
3. Routing so that every device on the network can be connected
4. Provide ip on the Forger, Desmond, Blackbell, and Briar subnets dynamically using the DHCP server. Then you remember that you have to set DHCP Relay on the router that connects it.

### Initial Node Conditions
![Topology modul 5](https://user-images.githubusercontent.com/112918215/206858332-4a0fc080-05a5-42d4-9691-f85cdfd8e6af.jpeg)

### IP Calculation
Deciding how many IP that are needed for each subnet and labeled the netmask as the amount of IP that are needed.
| Subnet| Alias | Total IP | Netmask | 
| ------ | ------ | ------ | ------ |
| A1 | westalis-eden-wise | 3 | 29 |
| A2 | westalis-forger| 63 | 25 |
| A3 | westalis-strix| 2 | 30 |
| A4 | strix-ostania| 2 | 30 |
| A5 | ostania-blackbell| 256 | 23 |
| A6 | ostania - briar| 31 | 26 |
| A7 | ostania - garden - sss| 3| 29 |
| A8 | owestalis - desmond | 701 | 22 |
| Total | ------ | 1061 | 21 |

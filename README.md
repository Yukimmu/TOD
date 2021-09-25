# TOD
## TOD Introduction
The full name of TOD is transit oriented development. It is an urban complex planning integrating commerce, culture, education and residence, which is established with a radius of 400-800 meters (about 5-10 minutes' walk) centered on public transport stations. Singapore Orchard Road complex, Tokyo Midtown, Hong Kong Kowloon Station and other world classic subway covered urban complexes belong to this kind.
# TOD Analysis Tool
TOD Analysis Tool is a tool to analyze the potential of TOD model construction. On a small scale, it can find stations suitable for the development of TOD mode. On a large scale, it can compare the development of TOD in different countries. Here is a picture of the Grasshopper Definition：
![picture1](https://user-images.githubusercontent.com/88954942/134769956-b0d61978-0fba-47eb-92de-bad0d63f6696.jpg)
## Use Instruction
- Input the information of one city here
![1](https://user-images.githubusercontent.com/88954942/134771455-d2559c76-8852-4610-b711-7919b2b5356c.jpg)
- Adjust the number bar to adjust the distance between the stations and each area. （Now it is set to “400m”）
![3](https://user-images.githubusercontent.com/88954942/134771464-421d52fc-950d-4e31-84d1-de02ef642900.jpg)
- Add new stations to find suitable construction stations.
![2](https://user-images.githubusercontent.com/88954942/134771493-bffdf3aa-e48b-489f-aef7-8f0f52cd4731.jpg)
- According to the TOD development potential map, planners can judge which site has great TOD construction potential and which site needs green space or business district to build TOD (The redder, the greater the potential for construction）.
![4](https://user-images.githubusercontent.com/88954942/134771497-423416fe-165c-49ee-b33c-24eefd5bf334.jpg)
![建造潜力表示](https://user-images.githubusercontent.com/88954942/134771504-57550594-6c06-451f-8150-b943af7c93df.jpg)
- The graph shows the connection status of different land uses and stations. This graph shows that the land use with low connectivity to stations is schools. That means that many schools are not built within a 400-meter radius of the station.
![5](https://user-images.githubusercontent.com/88954942/134771512-f6213ac0-3565-427c-a5b8-d9d13975deff.jpg)
## Outcomes
### Comparison between different stations in one country
TOD analysis tool can find out the rail transit stations with TOD development potential in the city, and it can let planners see what construction needs to be done if a rail transit station needs to develop into TOD mode. TOD Analysis Tool can also find suitable new stops with the potential to develop TOD by adding sites.
![建造潜力表示](https://user-images.githubusercontent.com/88954942/134771518-737caf2c-ccc2-47b4-9d18-13a4dbfe9ab3.jpg)
![建造潜力表示2](https://user-images.githubusercontent.com/88954942/134771522-8720d799-3c5f-4e41-b95a-b5c52b570555.jpg)
### Comparison between different countries
TOD analysis tool can compare the development of TOD in different countries, and use the table to show the connection status of various land and stations.
I used four sites of similar size in different cities to test my definition.
- Copenhagen
![哥本哈根总](https://user-images.githubusercontent.com/88954942/134771525-f1fc1041-39d1-46b5-8092-fa9a2138a065.jpg)
![哥本哈根有潜力的地方](https://user-images.githubusercontent.com/88954942/134771528-ff392a48-34f7-495f-b5d8-d0db79730ac0.jpg)
![哥本哈根数据](https://user-images.githubusercontent.com/88954942/134771535-d41b202d-baaf-4a27-8954-c1ba9779de88.jpg)![QQ截图20210922211821](https://user-images.githubusercontent.com/88954942/134771542-3aa7f99f-bce7-4bd2-82f7-b2030951b80f.jpg)
- Manila
![马尼拉总](https://user-images.githubusercontent.com/88954942/134771560-072e3d50-1bae-4682-9096-fa48343c7f03.jpg)
![马尼拉有发展潜力的地方](https://user-images.githubusercontent.com/88954942/134771566-f5d430f4-8eb3-4954-bf14-3e1ac0c0e96c.jpg)
![马尼拉数据](https://user-images.githubusercontent.com/88954942/134771567-134b560b-2151-48bf-8205-80e07dd82538.jpg)![QQ截图20210922211821](https://user-images.githubusercontent.com/88954942/134771568-09cab734-4aaa-4903-b429-6c65f301933c.jpg)
# Development
- Now I choose the way of color overlap to show the potential of TOD construction. This may not be a very suitable way of visualization. I need to make the final  outcome clearer.

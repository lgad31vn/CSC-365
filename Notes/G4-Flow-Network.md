# Flow Network

## Intro

![image](https://user-images.githubusercontent.com/66233296/165007766-cd5ad7ac-ef98-404c-af8e-689450401a0a.png)
![image](https://user-images.githubusercontent.com/66233296/165008212-97db0a02-d94b-428e-a7b6-3c7a2061584c.png)


- Pretty much Max Flow is the ``bottleneck`` value for the amount of flow that can pass through the network from source to sink under all the constraints
![image](https://user-images.githubusercontent.com/66233296/165006217-ec9cfefd-6f2a-43ea-ab74-b93173caf314.png)


## Max Flow
- Max flow is defined as the maximum amount of flow that the network would allow to flow from source to sink.
![image](https://user-images.githubusercontent.com/66233296/165132979-3599ab45-3328-48a1-a7e4-1d70e7f94f4d.png)


## Residual Graph
- The residual graph shows us where we can undo flow and where we can put more flow ==> Optimize how much flow we can push through our network
- The residual graph will have flows flow in the opposite directions compare to the original graph. This shows the directions the flows would flow back if we "undo" the flows

## Ford-Fulkerson Alogorithm
```
let f(e) = 0 with all edges
while s-t path in G-ressidual
  let p be a simple path in G-ressidual
  augment along path p
  update f to be f'
  update G-ressidual
end while
```




<!-- ![image](https://user-images.githubusercontent.com/66233296/165008263-008401f2-e365-4ea8-ba30-1505bed46faa.png)
![image](https://user-images.githubusercontent.com/66233296/165008380-0a1b9950-a4ee-4273-8cf4-d0f32ec4f817.png)
![image](https://user-images.githubusercontent.com/66233296/165008629-574d6c33-b930-401d-8881-06afe0bfe559.png)
 ![image](https://user-images.githubusercontent.com/66233296/165006052-1e832e5e-f126-4eef-a41b-f607f9d65d61.png)
 ![image](https://user-images.githubusercontent.com/66233296/165006306-84300e4d-e62a-4cbe-a021-a7e59c7455ba.png) -->
 
 
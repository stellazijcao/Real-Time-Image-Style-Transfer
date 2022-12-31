# Real-time Image Style Transfer

## Description
Style transfer is used to recomposing images (content images) in the style of other images (style images). The purpose of this project is to encourage innovative artistic creation. The potential use cases also include: video style transfer, VR in gaming and commercial art.

## Set Up
The system consists of a client, a server and a pretrained style transfer model. 
 - Client is used to send images to server and receive images from server. 
 - Server is used to receive images from client, call style transfer model, send processed images to client
 - Pretrained style transfer model is used to process images

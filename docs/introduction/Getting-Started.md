---
tags: [concepts, beginner, pos, terminal]
---

# Getting Started

Salt is finally here. 

As next generation POS solutions embrace the cloud, not only for e-Commerce but also in-store retail, there is a growing need for cloud hosted terminal solutions that make it easy for these POS solutions to connect with terminals that are in consumers hands. 

These terminals could conceptually be anything from a physical device to a digital wallet or banking application on a smartphone.

For now we will focus on the use case for a physical device and card present payment acceptance.

## The Ecosystem

Salt is currently partnering with several entities in the Iceland and UK market to facilitate a next generation universal acceptance platform. 

![Ecosystem](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/8b06f656-79c9-4f47-b69e-1ba1b0f04d7b/High_Level_Process_-_Page_1_%281%29.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20200514%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20200514T095718Z&X-Amz-Expires=86400&X-Amz-Signature=e24a94b0d18c5753a5d07126f59c791d8c107692686de2550c3a22cb18891e46&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22High_Level_Process_-_Page_1_%281%29.png%22 "Ecosystem")

## The Players

**Borgun**: Transaction acquirer. All merchants will be signed up as Borgun merchants and assigned a MID. 

**Handpoint**: Payment processor and client SDK technology provider. Handpoint will facilitate transaction processing between the terminal hardware and Borgun. 


## Transaction flow
When processing a transaction in a store, there are 4 main players involved.
1. The consumer, who wants to buy a product
2. The merchant, who stocks the product the consumer wants to buy
3. The Point of Sale (POS) software, which facilitates the sale and receipting for the merchant
4. The terminal, which facilitates the transaction against the consumers card 

The flow for the interaction during a sale is outlined below:
![Basic In-store Flow](http://rad2.wigroup.co/wigroup/wiplatform/uploads/basic-instore-flow.png "Basic In-store Flow")

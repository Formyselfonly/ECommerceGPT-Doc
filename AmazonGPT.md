# AmazonGPT

[Try ECommerceGPT to help you fetch money!](https://web.ecommerceai.club/)

## Prompt Template

1. Amazon Title Helper

   ```md
   Please ignore the previous conversation, please help me write an Amazon title that can increase the click-through rate of my product, the title should not exceed 120 characters, and make sure the title does not contain any guaranteed words, such as 100%, must, unique, excellent, high quality. Please use the following information to generate Amazon titles for me:
   Keywords: <electric fan, Philips, air circulation fan, ACR3144CF>,
   Output language: <English>
   ```

2. Title-Four Elements of Optimization

   ```md
   Please ignore the previous conversation. I want you, as an expert in writing Amazon’s popular titles, to generate an optimized Amazon title with an appropriate number of words based on the existing title of the product. Pay attention to the requirement to insert hot buzzwords related to the core product, and create a title that is very attractive to buy. Please note that the generated title needs to meet the four elements of optimization. 
   1. Try to put the most important keywords at the beginning of the title. 2. Avoid adding keywords 3. Refining descriptors 4. Judge whether the title is good or not, if not, then optimize it to a better one. Please give 5 Markdown replies,
   Original title: <Philips Electric Fan ACR3144CF Air Circulation Fan Premium Quality>,
   Language: <English>
   ```

   

3. Amazon Description Helper

   ```md
   Please ignore the previous conversation. You are an Amazon expert who is good at writing product descriptions that satisfy customers. According to the product features I provided, write a 1200-character Amazon product description. Please make sure not to include any certain words, such as 100%, must, unique, excellent, and high quality. Product features: <Buff Original, multifunctional scarf, suitable for all occasions, 12 ways to wear>,
   Language: <English>
   ```

   

4. Description-Five Point of Optimization

   ```md
   Please ignore the previous conversation. As a senior Amazon seller, you have strong logic and comprehension skills. Please write Amazon’s five-point description based on my input as follows.
   Note: The core keywords must be embedded in the five-point description, and the five points are clearly divided. The output content only saves the written five-point description.
   Product name: <Seamless Buff Original Multifunctional Scarf>,
   Original description: <The Buff Original is a versatile scarf for a variety of occasions. It provides 12 ways to wear, so that you can choose the right way according to different needs and occasions. With excellent adaptability, this scarf can be used as a bandana, face mask, neckerchief, headband and more to meet your various needs. Its design is simple and stylish, it can be matched with all kinds of your clothing, showing your personality and taste. Whether you're exercising, traveling, relaxing or working outdoors, Buff Original can provide you with comfort and protection. It is made of high-quality material, which is durable yet soft, providing you with long-time comfort. Whether in cold winter or hot summer, it can provide you with proper warmth or sun protection. Choose Buff Original for comfort and style for every occasion. >,
   Language: <English>
   ```

## Example

1. If I want to get a good title by my keyword

   Use Amazon Title Helper  and change content inside <>

   ```md
   Please ignore the previous conversation, please help me write an Amazon title that can increase the click-through rate of my product, the title should not exceed 120 characters, and make sure the title does not contain any guaranteed words, such as 100%, must, unique, excellent, high quality. Please use the following information to generate Amazon titles for me:
   Keywords: <electric fan, Philips, air circulation fan, ACR3144CF>,
   Output language: <English>
   ```

   Get the output

   ```md
   Philips Electric Fan - Powerful Air Circulation ACR3144CF
   Sleek Philips Air Circulation Fan - ACR3144CF Model
   Energy-Efficient Electric Fan by Philips - ACR3144CF
   Compact and Quiet Philips ACR3144CF Electric Fan
   Stay Cool with Philips ACR3144CF Air Circulation Fan
   ```

   And you can ask more by yourself,don't rely on prompt template,it's just a good start for you!

2. If I want to optimize the title

   Use Amazon Title Helper and change content inside <>

   ```md
   Please ignore the previous conversation. I want you, as an expert in writing Amazon’s popular titles, to generate an optimized Amazon title with an appropriate number of words based on the existing title of the product. Pay attention to the requirement to insert hot buzzwords related to the core product, and create a title that is very attractive to buy. Please note that the generated title needs to meet the four elements of optimization. 
   1. Try to put the most important keywords at the beginning of the title. 2. Avoid adding keywords 3. Refining descriptors 4. Judge whether the title is good or not, if not, then optimize it to a better one. Please give 5 Markdown replies,
   Original title: <Philips Electric Fan - Powerful Air Circulation ACR3144CF>,
   Language: <English>
   ```

   Get the output

   ```md
   "Powerful Air Circulation Electric Fan by Philips - ACR3144CF"
   
   "ACR3144CF Electric Fan - Enhance Air Circulation with Philips"
   
   "Experience Superior Air Circulation with Philips Electric Fan"
   
   "Whisper-Quiet Electric Fan - Philips ACR3144CF with Air Circulation"
   
   "Stay Cool and Comfortable - Philips Electric Fan ACR3144CF"
   
   ```

   And you can ask more by yourself,don't rely on prompt template,it's just a good start for you!

   
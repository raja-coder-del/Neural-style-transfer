# Neural-style-transfer

*COMPANY NAME*: CODTECH IT SOLUTIONS

*NAME*:TEKI RAJA

*INTERN ID*:CT06DM638

*DOMAIN*:Artificial intelligence

*DURATION*: 6 weeks 

*MENTOR*:Neela Santhosh Kumar

##DESCRIPTION##

Neural Style Transfer (NST) is a captivating deep learning technique that allows you to combine the content of one image with the artistic style of another. Imagine taking a photograph of a landscape and rendering it in the brushstrokes and color palette of a Van Gogh painting – that's essentially what NST achieves.

How it Works (The Core Idea):

NST operates by utilizing pre-trained Convolutional Neural Networks (CNNs), often models like VGG-16 or VGG-19, which have been trained on vast datasets for image recognition tasks. The key insight is that different layers within these CNNs capture different aspects of an image:

Content Representation: Higher-level layers in the CNN tend to capture the high-level features of an image, such as shapes, objects, and overall structure.

Style Representation: Lower-level layers capture more localized features like textures, colors, and brushstrokes, which contribute to the "style" of an image.

The process typically involves:

Input Images: You provide two images:

Content Image: The image whose objects and structure you want to preserve.

Style Image: The image whose artistic style (e.g., painting style, texture, color scheme) you want to apply.

Feature Extraction: Both the content and style images are passed through a pre-trained CNN. The activations from various layers are extracted.

Loss Functions: The heart of NST lies in defining and minimizing two main loss functions:

Content Loss: This measures the difference between the high-level features of the generated image (the output) and the content image. The goal is to ensure the generated image retains the spatial arrangement and objects of the content image.

Style Loss: This measures the difference between the stylistic features (often represented by Gram matrices, which capture correlations between feature maps) of the generated image and the style image. This encourages the generated image to adopt the textures, colors, and patterns of the style image.

Total Loss: The content and style losses are combined (usually as a weighted sum, where you can adjust the weights to prioritize content or style) to form a total loss function.

Optimization: An optimization algorithm (like gradient descent, often Adam) is used to iteratively update the pixels of a generated image (which typically starts as a noisy image or a copy of the content image) to minimize the total loss. This means the generated image is constantly adjusted until it simultaneously looks like the content image in terms of structure and the style image in terms of artistic flair.

Applications of Neural Style Transfer:

NST has a wide range of creative and practical applications:

Artistic Creation: This is the most common application, allowing users to transform their photographs into artworks resembling famous paintings or to create entirely new artistic pieces by blending different styles. Mobile apps like DeepArt and Prisma are popular examples.

## for this project##
# requirements#
--------------------------------------------------
=> google colab or jupyter notebook

=> Different artistic images

i preferred google colab because it provides free runtime environment and gpu support

first go to google colab and sign in with registered mail .if user no account just registered a new user by clicking the singup page with cerdentials. then open a new notebook in drive. then paste the code and run the code cell by cell.

note : you can use pre trained model for these user can get model in two ways
1. visiting the model hub and select model copy url and paste it code.
2.  if it is not work use the given model
   
  model = hub.load('https://tfhub.dev/google/magenta/arbitrary-image-stylization-v1-256/2')

you can upload your local images by going through these steps click on file then content then click on upload images from local devices.once it done it shows files in content area then copy the file path , the path will used in code section just simple paste the path copied earlier.

## steps in execution##

1. Import Dependencies and Pretrained Model
   
2.Preprocess Image and Load

3.Visualize Output

4. Stylize Image

## visual image##

![Image](https://github.com/user-attachments/assets/782831eb-c71b-4759-8346-1e283664e3f9)

## output image##
![Image](https://github.com/user-attachments/assets/f12d704c-f2e9-4430-91ea-a00275f9a7c6)

                                                                                                       For any quries and issues contact me:
                                                                                                       tekiraja143@gmail.com


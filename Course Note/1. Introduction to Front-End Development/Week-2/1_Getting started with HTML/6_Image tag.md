Date: 2080/07/11
By: [Saroz Pokhrel](https://www.sarozpokhrel.com.np)

**Image Tag (`<img>`) in HTML**:

The `<img>` tag, commonly known as the image tag, is used to add images to HTML documents. It creates a placeholder for an image on a webpage and references the image file using the `src` attribute. Here's a breakdown of how to use the image tag and its attributes:

1. **Adding Images**:
    
    - To add an image to a webpage, you use the `<img>` tag and specify the image file's location using the `src` (source) attribute.
    
    Example:
    
    html
    
    `<img src="falafel.jpeg" alt="A falafel"> <img src="salad.jpeg" alt="A pasta salad">`
    
    In this example, two images ("falafel.jpeg" and "salad.jpeg") are added to the webpage.
    
2. **Specifying Dimensions**:
    
    - You can set the dimensions (width and height) of an image by using the `width` and `height` attributes. This controls the size of the displayed image on the webpage.
    
    Example:
    
    html
    
    `<img src="falafel.jpeg" alt="A falafel" width="240" height="135"> <img src="salad.jpeg" alt="A pasta salad" width="240" height="135">`
    
    In this example, both images are set to a width of 240 pixels and a height of 135 pixels.
    
3. **Alt Text (Alternative Text)**:
    
    - It's considered good practice to provide alternative text for images using the `alt` attribute. This text is not displayed on the webpage but serves as a description of the image. It's vital for accessibility, as screen readers use it to describe images to users with visual impairments.
    
    Example:
    
    html
    
    `<img src="falafel.jpeg" alt="A falafel"> <img src="salad.jpeg" alt="A pasta salad">`
    
    In this example, "A falafel" and "A pasta salad" are provided as alt text for the respective images.
    

Including alternative text is important for making web content more accessible to all users and can also have SEO benefits.

- **Summary**:
    - The `<img>` tag is used to display images on a webpage.
    - The `src` attribute specifies the image file's source.
    - The `alt` attribute provides alternative text for the image.
    - The `width` and `height` attributes control the image's dimensions.

Images enhance the visual appeal and user experience of websites, and adding them with appropriate alt text ensures inclusivity and accessibility.
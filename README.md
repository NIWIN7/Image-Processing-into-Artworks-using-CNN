# Image-Processing-into-Artworks-using-CNN

Neural style transfer recently has become one of the most popular topics in academic research and industrial application. The existing methods can generate synthetic images by transferring different styles of some images to another given content images, but they mainly focus on learning low-level features of images with losses of content and style, leading to greatly alter the salient information of content images in the semantic level. In this paper, an improved scheme is proposed to keep the salient regions of the transferred image the same with that of content image. By adding the region loss calculated from a localization network, the synthetic image can almost keep the main salient regions consistent with that of original content image, which helps for saliency-based tasks such as object localization and classification. In addition, the transferred effect is more natural and attractive, avoiding simple texture overlay of the style image. Furthermore, our scheme can also extend to remain other semantic information (such as shape, edge, and color) of the image with the corresponding estimation networks.
# Modules: 
# Color Quantization:
• reduces the range of different colours inside the photograph so that the brand new photograph is visually similar and compressed in length.
• General case: converting a 24-bit coloration picture to an 8-bit color picture.
• K approach clustered institution factors of the same color.
• K cluster centroids represent the 3D RGB colour area and replace the colors of all factors within the cluster, ensuing in an photo with K colours.

# Super pixel Segmentation
• Split the photograph into superpixels. A superpixel is a group of associated elements with comparable colorings or grey ranges.
• It makes use of a random segmentation technique called easy linear iterative clustering (SLIC). Segment the photo the use of K to symbolize the fringe.
• takes all of the pixel values of the image and tries to divide them right into a predefined quantity of subregions.

# Neural Style Transfer:
• An optimization approach that combines the content material of an image with the style of some other photograph, correctly conveying the fashion.
• Image content: the shape of gadgets, their unique format and vicinity.
• Image fashion: color, texture, patterns in pieces, fashion of modifying.
• Capable of producing breathtaking results which can be difficult to attain manually.
• As below, the output corresponds to the content of the statistical photograph and the fashion of the image changes. These data are extracted from the pics the use of a convolutional neural network.
• Simply positioned, the generated photograph is similar to the content material of the photo, however as if drawn via Van Gogh within the style of Starry Night.

# Proposed system 
Neural style transfer is an optimization technique used to take two images—a content image and a style reference image (such as an artwork by a famous painter)—and blend them together so the output image looks like the content image, but “painted” in the style of the style reference image.


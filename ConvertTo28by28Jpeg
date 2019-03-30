import PIL
from PIL import Image
basewidth = 28
img = Image.open('underArmorShoe.jpeg')
wpercent = (basewidth / float(img.size[1]))
hsize = int((float(img.size[1]) * float(wpercent)))
img = img.resize((basewidth, 28), PIL.Image.ANTIALIAS)
img.save('resized_image.jpg')

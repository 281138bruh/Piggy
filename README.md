# Piggy

# Create a blank canvas for the infographic
width, height = 800, 1200
img = Image.new('RGB', (width, height), color=(255, 255, 255))
d = ImageDraw.Draw(img)

# Title
title_font = ImageFont.load_default()
d.text((10, 10), "Piggy from Lord of the Flies: Character Analysis", fill=(0, 0, 0), font=title_font)

# Add sections
section_font = ImageFont.load_default()

# Character Background
d.text((10, 50), "Character Background:", fill=(0, 0, 0), font=section_font)
d.text((10, 70), "Piggy is an intellectual boy with glasses,", fill=(0, 0, 0), font=section_font)
d.text((10, 90), "asthma, and is often ridiculed by others.", fill=(0, 0, 0), font=section_font)
d.text((10, 110), "He introduces the conch to maintain order.", fill=(0, 0, 0), font=section_font)

# Character Development
d.text((10, 150), "Character Development:", fill=(0, 0, 0), font=section_font)
d.text((10, 170), "Piggy tries to maintain civilization and order,", fill=(0, 0, 0), font=section_font)
d.text((10, 190), "but his death represents the loss of reason", fill=(0, 0, 0), font=section_font)
d.text((10, 210), "and the collapse of society.", fill=(0, 0, 0), font=section_font)

# Relationships
d.text((10, 250), "Relationships:", fill=(0, 0, 0), font=section_font)
d.text((10, 270), "Piggy supports Ralph but faces opposition", fill=(0, 0, 0), font=section_font)
d.text((10, 290), "from Jack. His relationship with Ralph evolves", fill=(0, 0, 0), font=section_font)
d.text((10, 310), "as civilization gives way to savagery.", fill=(0, 0, 0), font=section_font)

# Symbolic Significance
d.text((10, 350), "Symbolic Significance:", fill=(0, 0, 0), font=section_font)
d.text((10, 370), "Piggy represents intellect and civilization.", fill=(0, 0, 0), font=section_font)
d.text((10, 390), "His death symbolizes the collapse of order", fill=(0, 0, 0), font=section_font)
d.text((10, 410), "and the rise of savagery.", fill=(0, 0, 0), font=section_font)

# Discussion Questions
d.text((10, 450), "Discussion Questions:", fill=(0, 0, 0), font=section_font)
d.text((10, 470), "1. How does Piggy's intellect influence his relationships?", fill=(0, 0, 0), font=section_font)
d.text((10, 490), "2. What does Piggy's death symbolize?", fill=(0, 0, 0), font=section_font)
d.text((10, 510), "3. What role does Piggy play in Ralph's leadership?", fill=(0, 0, 0), font=section_font)
d.text((10, 530), "4. How does Piggy balance Jack's savagery?", fill=(0, 0, 0), font=section_font)
d.text((10, 550), "5. Would Piggy have survived if physically stronger?", fill=(0, 0, 0), font=section_font)

# Save the image
infographic_path = '/mnt/data/piggy_infographic_v3.png'
img.save(infographic_path)

# Provide the link to the user
infographic_path

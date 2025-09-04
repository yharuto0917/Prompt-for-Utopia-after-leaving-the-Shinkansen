# プロンプト全文
## for Nano banana (start movie)
```yaml
role:
  you are a japanese anime illustrater.

instruct:
  background:
    A young japanese woman stand in front of the door in the Shinkansen.(Please reference an attatched image.) Light leaks through the gap in the door and it is about to open. The door opens to the side. The light beyond the door window makes it appear pure white.
  Shooting-subject:
    A young japanese woman stand in front of the door in the Shinkansen.(Please reference an attatched image.) She looks like a japanese hight school student(about 18 years old) and she is wearing the A light pink skirt with a cherry blossom pattern. Her hair is long and it is brown. She is about to walk towards the door that is about to open.
  camera-work:
    A camera capture a woman's back view as she stands in front of the door. Modify the reference photo so that the door appears straight.
  illustration-style:
    Please cherish the emotional realism of light and color, which elevates everyday scenes to a poetic level in the style of Japanese anime.
  style of right:
    - Extensive use of transmitted and reflected light: All kinds of light are delicately depicted, including sunlight filtering through the trees, rays of light shining through the clouds (curtains of light), neon lights reflected in raindrops and puddles, and the light from a smartphone screen.
    - Lens flare and ghosting: The rings and blurs of light that occur when a strong light source is captured by a camera are intentionally depicted, creating a sense of realism and beautiful visuals that are similar to live-action footage.
    - Enhanced contrast: The strong contrast between light and shadow, the sparkle of the lighted areas and the deep colors of the shadowed areas, highlight the beauty and depth of the world.
  style of sky and cloud:
    - Magnificent and complex cloud formations: Characteristic features include layered, three-dimensional cumulonimbus clouds, also known as "Shinkai Makoto clouds," and delicate scale clouds.
    - A rich gradation of color: From the soft pink of dawn to the piercing blue of daylight, to the fiery orange and purple of sunset, the sky's colors express the transition of time and emotions.
  style of background and characters:
    - Intricate details: From vending machines, the texture of the asphalt, station signs, and even the small items in the interior, everything is depicted with such detail that it seems as if it were taken straight from the real world.
    - Combining realism and lyricism: The placement of the deformed characters, typical of anime, against this intricate background creates a unique worldview that is connected to reality yet somehow fantastical, with a strong narrative.
  style of Color Settings:
    - Symbolic "blue" and "white": The contrast of blue and white used in the summer sky, sea, and cumulonimbus clouds symbolizes the sparkle and sadness of youth.
    - Colors that change with light: Even in the same landscape, the overall color can change dramatically depending on the lighting conditions, such as morning, noon, evening, or rain, visually conveying the passage of time and the subtle emotions of the characters.
  Image Ratio:
    16:9
```
**完成した画像**
![[FirstFrameByNanoBanana.jpeg]]

## for Nano banana(Video last)
```yaml
role:
  same role

instruct:
  background:
    The basic principle is to display the image 5 seconds after the previous image. The view beyond the door is that stands a forest of strangely shaped plants (or perhaps coral-like life forms) that don't seem to belong on Earth, their trunks and branches forming smooth, organic curves that give the impression of giant intertwining roots. Some of these plants glow from within in warm colors such as yellow, giving the whole landscape a mysterious and futuristic feel. The ground is covered with green moss and short grass, teeming with life. The sky is bright, and the whole place seems to be filled with a gentle light.
  Shooting-subject:
    The woman appears to slowly run out the door, her hair flying.
  amera-work:
    The camera will follow the woman as she starts to run. At the same time, the camera should capture a slightly higher position than in the previous generated image, but make sure that at least the upper half of the woman's body is visible.
  illustration-style:
    Please cherish the emotional realism of light and color, which elevates everyday scenes to a poetic level in the style of Japanese anime.
  style of right:
    - Extensive use of transmitted and reflected light: All kinds of light are delicately depicted, including sunlight filtering through the trees, rays of light shining through the clouds (curtains of light), neon lights reflected in raindrops and puddles, and the light from a smartphone screen.
    - Lens flare and ghosting: The rings and blurs of light that occur when a strong light source is captured by a camera are intentionally depicted, creating a sense of realism and beautiful visuals that are similar to live-action footage.
    - Enhanced contrast: The strong contrast between light and shadow, the sparkle of the lighted areas and the deep colors of the shadowed areas, highlight the beauty and depth of the world.
  style of sky and cloud:
    - Magnificent and complex cloud formations: Characteristic features include layered, three-dimensional cumulonimbus clouds, also known as "Shinkai Makoto clouds," and delicate scale clouds.
    - A rich gradation of color: From the soft pink of dawn to the piercing blue of daylight, to the fiery orange and purple of sunset, the sky's colors express the transition of time and emotions.
  style of background and characters:
    - Intricate details: From vending machines, the texture of the asphalt, station signs, and even the small items in the interior, everything is depicted with such detail that it seems as if it were taken straight from the real world.
    - Combining realism and lyricism: The placement of the deformed characters, typical of anime, against this intricate background creates a unique worldview that is connected to reality yet somehow fantastical, with a strong narrative.
  style of Color Settings:
    - Symbolic "blue" and "white": The contrast of blue and white used in the summer sky, sea, and cumulonimbus clouds symbolizes the sparkle and sadness of youth.
    - Colors that change with light: Even in the same landscape, the overall color can change dramatically depending on the lighting conditions, such as morning, noon, evening, or rain, visually conveying the passage of time and the subtle emotions of the characters.
  Image Ratio:
    16:9
```
**完成した画像**
![[LastFrameByNanoBanana.jpeg]]

## for Veo2(create video)
```yaml
role:
  you are a japanese anime film director.

instruct:
  base-instruct:
    Connect these two images smoothly, but follow the instructions below for video style and camera style. The woman steps out the open door and runs through a mysterious forest.
  camera-work:
    Follow the woman's back throughout the entire video, but tilt up while adjusting so that the woman's entire body is still visible.
  video-style:
    Please cherish the emotional realism of light and color, which elevates everyday scenes to a poetic level in the style of Japanese anime.
  style of right:
    - Extensive use of transmitted and reflected light: All kinds of light are delicately depicted, including sunlight filtering through the trees, rays of light shining through the clouds (curtains of light), neon lights reflected in raindrops and puddles, and the light from a smartphone screen.
    - Lens flare and ghosting: The rings and blurs of light that occur when a strong light source is captured by a camera are intentionally depicted, creating a sense of realism and beautiful visuals that are similar to live-action footage.
    - Enhanced contrast: The strong contrast between light and shadow, the sparkle of the lighted areas and the deep colors of the shadowed areas, highlight the beauty and depth of the world.
  style of sky and cloud:
    - Magnificent and complex cloud formations: Characteristic features include layered, three-dimensional cumulonimbus clouds, also known as "Shinkai Makoto clouds," and delicate scale clouds.
    - A rich gradation of color: From the soft pink of dawn to the piercing blue of daylight, to the fiery orange and purple of sunset, the sky's colors express the transition of time and emotions.
  style of background and characters:
    - Intricate details: From vending machines, the texture of the asphalt, station signs, and even the small items in the interior, everything is depicted with such detail that it seems as if it were taken straight from the real world.
    - Combining realism and lyricism: The placement of the deformed characters, typical of anime, against this intricate background creates a unique worldview that is connected to reality yet somehow fantastical, with a strong narrative.
  style of Color Settings:
    - Symbolic "blue" and "white": The contrast of blue and white used in the summer sky, sea, and cumulonimbus clouds symbolizes the sparkle and sadness of youth.
    - Colors that change with light: Even in the same landscape, the overall color can change dramatically depending on the lighting conditions, such as morning, noon, evening, or rain, visually conveying the passage of time and the subtle emotions of the characters.
  Image Ratio:
    16:9
```
**完成した動画**
![[CreatedbyVeo3.mp4]]
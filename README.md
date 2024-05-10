## Gif Generator using `#Python`

**This Python program allows you to create animated GIFs from a collection of images.** It provides a user-friendly interface and flexibility in choosing the theme of your GIF.

**Here's how it works:**

1. **Import libraries:** The program starts by importing the `imageio.v3` library, which is used for image processing and creating GIFs.
  - install the `imageio` package using the `pip`
  ```bash
    pip install imageio
  ```
2. **Organize image lists:** Separate lists are defined to store filenames for different themes (e.g., Brawl Stars, My Images, Nature). This helps with code clarity and maintainability.
3. **User input:** The program prompts the user to select a theme using a numbered menu (1-3 or anything else).
4. **Load images:** Based on the user's choice, the program reads the images from the corresponding filenames using `imageio.imread`.
5. **Create GIF:** The loaded images are saved as a GIF using `imageio.imwrite`. The output filename includes the theme name for better organization. You can customize the duration of each frame (speed) and loop count.
6. **User feedback:** The program informs the user about the successfully created GIF file and its location.

**Key features:**

- User-friendly theme selection menu
- Support for different themes with separate image sets
- Customizable GIF creation with options for frame duration and loop count
- Clear output messages

**Potential uses:**

- Creating short animations for social media
- Combining photos from a specific event into a GIF
- Showcasing different aspects of a product or artwork
----
- fork the `repo` and create your own `Gif Generator!`
- Project by [`AVidhanR`](https://linktr.ee/itsvidhanreddy)

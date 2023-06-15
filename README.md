# Thinkfulbnb

Thinkfulbnb is a vacation rental website that allows people to rent out their homes to people who are seeking short-term accommodations in that locale. Thinkfulbnb hosts rent out different kinds of properties, including single rooms, apartments, and unique living spaces such as yachts, houseboats, yurts, tiny houses, and even renovated medieval castles.

For this assignment, you will implement Thinkfulbnb's landing page in HTML & CSS.

## Thinkfulbnb views

The UX designer provided you with the following user interface mockups:

### Mobile view

![](images/Thinkfulbnb-mobile.png)

### Desktop view

![](images/Thinkfulbnb-desktop.png)

### Existing files

| File         | Description                                                             |
| ------------ | ----------------------------------------------------------------------- |
| `images/`    | A folder containing all the images used for the design.                 |
| `index.html` | The starter HTML file. You will need to add your solution to this file. |
| `style.css`  | The starter css file. You will need to add your solution to this file.  |

You're encouraged to spend some time studying the provided files.

### Setup

Use VSCode Live Server to launch the `index.html` page in your browser.

### Tasks

For this assignment, you will be following a mobile-first development approach. To pass this assignment, you must complete the tasks detailed below.

You **should** use flexbox, and **not** floats, to achieve the desired layouts. The `.group`, `.item`, and `.item-double` classes are provided in the CSS file for your convenience, but it is not necessary to use them.

You are **NOT** expected to match the designs pixel by pixel, as long as the required layout is satisfied.

Edit the `index.html` and `style.css` as needed to achieve the following requirements:

#### Navigation

- The logo should stack on top of the menu links, which are aligned horizontally, as follows:

![Navigation mobile](./images/navigation-mobile.png)

- **Single-page navigation**: Modify the navigation links so that clicking on each link will take the user to the corresponding sections on the page, as follows:

| Link clicked | Take the user to the section with `id` of |
| ------------ | ----------------------------------------- |
| `Stay`       | `id="stay"`                               |
| `About`      | `id="about"`                              |
| `Ideas`      | `id="ideas"`                              |
| `Host`       | `id="host"`                               |

#### HTML form

- In the "Find your perfect vacation rental" section, create a form that contains the following input fields with the specified types:

  - `Location`: `text` input type, with a placeholder value of "Search destination"
  - `Arrive`: `date` input type
  - `Depart`: `date` input type
  - `Type`: a dropdown list with the following options:
    - Apartment
    - Barn
    - Castle
    - Houseboat
    - Tiny House
    - Yacht
    - Yurt
  - a `"Search"` button

- Some CSS styles have already been written for you to help style your form. Add CSS to the form so that
  - the labels (i.e., "Location", "Arrive", "Depart", "Type") and their corresponding form fields are aligned towards the opposite ends of each row

Your final form design should look as follows:

![Search form mobile](./images/search-form-mobile.png)

#### Vertical content alignment

- The content in the remainder of the sections (i.e., "About", "Ideas", "Want to become a Thinkfulbnb Host?"), including any text and images, should stack on top of each other. Refer to the mobile design shared above.

#### Responsive images

- Write CSS for all images so that the images will match whatever container width they are placed within, and changing the container sizes will update the image sizes appropriately.

#### Media query: Desktop view

Now that your mobile design is looking good, you will need to adapt the design for the desktop view.

- In `style.css`, create a media query for screens that are wider than `480px`.

Within the media query, write CSS to create the following designs for desktop:

- The logo and the navigation menu links should be spaced apart from each other, like this:

![Navigation desktop](./images/navigation-desktop.png)

- The search form input fields and the button should be horizontally aligned, like this:

![Search form desktop](./images/search-form-desktop.png)

- The items in the "About" section should be horizontally aligned. The paragraph content should be vertically centered and always be about twice as wide as each image item, like this:

![About desktop](./images/about-desktop.png)

- The "Ideas" images should be displayed in a 2 by 2 grid (see the desktop design shared above).

- The items in the "Want to Become a Thinkful Host?" section should be horizontally aligned. The paragraph content should be vertically centered and be as wide as each image item, like this:

![Host desktop](./images/host-desktop.png)

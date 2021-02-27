// TFN DESIGN SYSTEM <<--THE FRONTEND NINJA DS->> //

TFN DESIGN SYSTEM - Was crafted baded on the "Atomic Design Model"

// ➡ Atomic Design ?
//---------------------------------

Atomic Design provides a clear methodology for crafting design systems that promote consistency and scalability. Without being a linear process, we can adopt the practices that best fit our needs.

// ➡ Atoms
//---------------------------------

Atoms can include more abstract elements like color, text styles or icons.

// ➡ Molecules / Components
//---------------------------------

Molecules, Components are groups of atoms bonded together to form a button, an input or a form label.

// ➡ Organisms
//---------------------------------

Organisms are groups of molecules, compoentents joined together to form a relatively complex, distinct section of an interface, like a header, footer or a card.

What 'TFN DS' covers?

- All required global stuff will be covered as per the atoms Organisms will be partially because that's based on your project requirement you build with atoms and Molecules / Components.

Benfits of TFN DS ?

- Building core global atoms which will be easy to develop exceptional UI, UX for mobile and web. No framework depedencies and updates.

How to use ?

- Refer this TFN DS global ➡ 📁 in your project theme folder where you can customize as per your needs, as well trying to make much simpler Design system to use and expand in large scale applications

global/
|
|– base/
| |– \_colors.scss # color palette
| |– \_typography.scss # Typography rules
| ... # Etc…
|
|– components/
| |– \_buttons.scss # Buttons
| |– \_card.scss # Card
| |– \_chip.scss # Chip
| |– \_forms.scss # Form Elements
| ... # Etc…
|
|– dependencies/
| |– \_variables.scss # Sass Variables
| |– \_functions.scss # Sass Functions
| |– \_mixins.scss # Sass Mixins
| |– \_helpers.scss # Class & placeholders helpers
|
|– vendors/
| |– \_bootstrap.scss # Bootstrap
| ... # Etc…
|

Files should be imported according to the folder they live in, one after the other in the following order:

dependencies/
vendors/ << Optional >>
base/
components/

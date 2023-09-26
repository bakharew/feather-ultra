# Feather Ultra

Feather Ultra is a multiplatform, open-source analogue to animated SF Icons. This beautifully animated, rive-powered tool can help you add microinteractions to your product.

👉 [See the Demo Here](https://featherultra.com)

👉 [Playground Link](https://rive.app/community/6079-11905-feather-ultra-v-011) 


## Features
- Swap icons
    - Simple swap (from any icon to any other)
    - Switch current icon to loader (boolean)
    - Ping-Pong swap (icon changes to a new icon and then back to the original)
    - Switch current icon to loader and, once boolean is unticked, to a new icon
- Change icon stroke width (from 0.5 to 3)
- Predefined icon color setup:
    - Danger
    - Warning
    - Success
    - Normal
    - Hover
    - White
    - Yellow

> [!NOTE]
> Rive currently does not support programmatically changing colors during runtime. However, we've got you covered! You can utilize predefined color variables and customize them according to your brand colors. Use the super-fast `color_change.ipynb` script to change color variables and get your custom-colored binary without the need to import rev into the editor, and then reexport it as riv (which requires a paid Rive subscription).

- Trigger icon animations (trigger)
    - Hover
    - Scale
    - Bounce
- Set icon animations (boolean)
    - Hover
    - Pulse

## Icons Availability Status
- 13 out of 287 icons are currently ready

## Roadmap

- Finalize icon animations from the original feather icons set
- Support changing to any color in runtime (we're waiting for rive to support this, as it currently doesn't support color changes in runtime)
- Develop quick start guides for popular platforms (contributors needed)
- Create npm package for easier implementation (contributors needed)


## License

Feather Ultra is licensed under the [MIT License](https://github.com/feathericons/feather/blob/master/LICENSE).
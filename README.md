# 80forty Keyboard

The utility of an 80% keyboard in a 40% form factor.

Inspired by the design of the [OP-1 Synthesizer](https://teenage.engineering/store/op-1-field/), the explorative spirit of the 40% & 30% keyboard community (especially boards like ChonkyKong, CutiePie, and Ortho Cajal), and the tactile reference points and minimized finger-travel of many split, ergonomic keyboards. The 80forty was partly motivated by the appearance of [Deadline Studio DOYS keycaps](https://deadline.space/products/doys-keycaps), but it works with any MX-compatible keycaps.

The 80forty has a layout that is ortholinear and minimal, but still retains the keys that are helpful for everyday computing and specialized tasks like graphic design applications (i.e. arrow keys, bottom mod keys, and outer columns allowing for e.g. dedicated shift and backspace keys). It also allows either a knob or a 2x2 macropad above the arrow keys.

Supports low-profile KS33 switches (with hotswap sockets) as well as MX switches (soldered/mill-maxed).

![Overview of 80forty with the v1 stacked acrylic case](https://github.com/arrowtype/80forty/blob/main/images/80forty-repo-hero_image.jpg?raw=true)

## V1 Case Designs

Version 1 uses either a stacked acrylic or ”skeleton” FR4 plate design.

While the PCB supports either KS33 or MX switches, the current case designs have only been settled for the KS33 switches. MX switches require more space, and would likely require larger middle case layers.

### Stacked Acrylic Case

This case uses the standard FR4 top plate of the 80forty, and sandwiches it in a few layers of 5mm, lasercut acrylic.

![Side view of 80forty keyboard with stacked acrylic case](https://github.com/arrowtype/80forty/assets/45946693/fb458766-9641-4913-a890-6a5d060a5825)

![Bottom view of 80forty keyboard with stacked acrylic case](https://github.com/arrowtype/80forty/assets/45946693/da6e7aff-e629-48d0-85e6-07347c3c8141)

### Skeleton FR4 Case

This case uses the standard FR4 top and bottom plates of the 80forty, with standoffs providing middle separation for the switches.

![Close-up view of 80forty keyboard with skeleton FR4 case](https://github.com/arrowtype/80forty/assets/45946693/7f9dc68f-2087-4758-ac63-f5a6176eb8ea)

![Profile view of 80forty keyboard with skeleton FR4 case](https://github.com/arrowtype/80forty/assets/45946693/ec4543be-f3c3-4d07-b83d-73357ced653b)

![Close-up bottom view of 80forty keyboard with skeleton FR4 case](https://github.com/arrowtype/80forty/assets/45946693/d49351ab-737a-415d-924b-420b38618804)

## Configuration Options

Configurable with either 1 large knob or 4 macro keys.

![80forty-knob](https://github.com/arrowtype/EightyForty/assets/45946693/39bb6fa5-88dd-4389-a4f0-af48277507c1)

![80forty-macro](https://github.com/arrowtype/EightyForty/assets/45946693/74899e76-7505-49b7-8cb2-fdf65c2adc61)

## Keymaps

80forty is configurable in Vial, so the keymap can be whatever you want! However, here are two example layouts to show what might be common approaches to such a keyboard.

The 2-unit spacebars are intended to serve double duty: to input `Space` when tapped, or to shift to respective layers when held.

![80forty-example-keymap-simpler](https://github.com/arrowtype/80forty/assets/45946693/0aa5de20-beb3-41ef-906a-f904df8a2029)

Vial/QMK also allow for “key combos.” So, for instance, it is possible to forgo a dedicated `Escape` key and instead assign this to `Tilde` + `Q`.

![80forty-example-keymap](https://github.com/arrowtype/80forty/assets/45946693/3eb43e1b-913e-43b0-952c-bab3bc9b8cc1)


## Future Vision

The project was conceived to allow a sleek, low-profile, CNC aluminum case design. This is still a goal, but there is no current timeline for this version.

In the slightly nearer term, the intention is to prototype this case with 3D printing. If anyone out there is interested in creating this 3D case and contributing it to the project, let us know in the issues or in a pull request!

![8040 Knob](https://github.com/arrowtype/EightyForty/assets/45946693/5f2414e0-8bce-41f5-8451-36dc80e66794)

![8040 Macro](https://github.com/arrowtype/EightyForty/assets/45946693/546b121b-736e-438a-a96e-64aad3fe3442)

## Credits

Concept, layout, case design, and PCB graphics by Stephen Nixon / ArrowType.

Engineering, code, and PCB specifications and ordering by Noah Kiser / Kiser Designs.

## To be continued!

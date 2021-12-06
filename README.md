## Running

    cd metapoker-website
    python3 -m http.server

View the website at http://127.0.0.1:8000/

Play around with start position, scale, and rotation until the scene works. Increase timeout if necessary.

## [A-FRAME][1]

The VR experience is built by importing [3D-models][3] into A-FRAME


## [`position="x y z"`][2]

| Axis | Description |
| :-:  | :----       |
| `x`  | Negative X axis extends left. Positive X Axis extends right. |
| `y`  | Negative Y axis extends down. Positive Y Axis extends up.    |
| `z`  | Negative Z axis extends in. Positive Z Axis extends out.     |

  [1]: https://aframe.io/docs/1.2.0/introduction/
  [2]: https://aframe.io/docs/1.2.0/components/position.html
  [3]: https://aframe.io/docs/1.2.0/introduction/models.html

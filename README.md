# Coulomb — Electrostatic Field Visualizer

An interactive point-charge electric field simulator. Place positive and negative charges, watch field lines trace themselves in real time, and probe the field with a test charge.

## Features

- Click to place positive/negative point charges, drag to move them, alt-click to delete
- Field lines traced numerically outward from positive charges (streamline integration, not a static arrow grid)
- Field magnitude heatmap toggle
- Draggable test charge showing the local force vector
- Live cursor readout: position, field magnitude, direction, and potential
- Touch support, no build step, no dependencies


## Possible extensions

- Equipotential contour lines (marching squares) alongside the heatmap
- Save/load charge configurations as JSON
- Continuous charge distributions (line charge, ring, disk)
- Energy of the configuration displayed live as charges move

## License

MIT

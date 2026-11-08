![The brought in piece and the standard trial plates close up side by side in the open velvet lined case, red assay marks on the nearest pieces, the assayer's gloved hand at the frame edge](intro-banner.png)

> Medium noted first: gilding, gold leaf on a leather cushion, Caveat Brush in indigo on resist white, a stores list entry.

# cdd-configdrift-BaselineDiff

![A rectangular gold trial plate resting plain and unmarked in its slot in an oxblood velvet lined case, one small red assay mark stamped at its corner, the heading plate](logo.png)

![An assayer in gloves at a bench holding a brought in gold piece beside the open case of gold and silver trial plates, a balance and touchstones at the bench edge](banner.png)

![The bench in three bands: light moves along the brush jars, a tissue page lifts a fraction over the leaf book, and a line of light travels once across the cushion from the untouched leaf toward the cut square, pausing at the knife](scene.svg)

# cdd-configdrift-BaselineDiff
Compares current configuration against a known good baseline, highlighting differences in a readable format (e.g., using `diff` or similar library). - Focused on This category encompasses tools designed to detect changes in configuration files over time. This allows security teams to identify unauthorized modifications, deviations from established baselines, and potential misconfigurations that could introduce security risks. The tools track and highlight differences across versions, aiding in rapid troubleshooting and remediation.

![A major divider: a full row of brush stroke gradient tests stepping from indigo to copper](sep-heavy.svg)

## Install
`git clone https://github.com/ShadowStrikeHQ/cdd-configdrift-baselinediff`

![A minor divider: three short brush test strokes at the centre](sep-light.svg)

## Usage
`./cdd-configdrift-baselinediff [params]`

> Leaf book tissue panel: the usage line names neither side of the comparison. It names neither the current configuration nor the baseline it is to be compared with, although comparison between two states is the tool's whole task.

![A major divider: a full row of brush stroke gradient tests stepping from indigo to copper](sep-heavy.svg)

## Parameters
- `-h`: Show help message and exit
- `--format`: No description provided
- `--ignore`: List of keys to ignore in the diff
- `--output`: Path to the output file for the diff. If not specified, diff is printed to stdout.
- `--indent`: No description provided
- `--no-color`: Disable color output.

> Leaf book tissue panel: --format and --indent arrive with no description provided. No meaning is guessed for either of them.

![A major divider: a full row of brush stroke gradient tests stepping from indigo to copper](sep-heavy.svg)

## License
Copyright (c) ShadowStrikeHQ

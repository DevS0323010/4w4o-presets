# 4W4O Presets: Presets for the 4W4O Synthesizer

This is the repositiory of custom presets of the 4W4O synthesizer.

## How to Load the Presets

1. Download the `presets/` folder from this repository.
2. Load the presets in one of the following ways:
   1. Use Python code to load the presets:

   ```python
   from synth.synth import Synth
   s = Synth()
   s.read_from_file("presets/default.json")
   ```

   2. Use the GUI to load the presets:
      1. Launch the GUI:

      ```bash
      python main.py 
      ```

      2. Click `Open` and select one of the `.json` files in the `presets/` directory.

## Preset JSON Format

Check the [main repository](https://github.com/DevS0323010/4w4o-python) for more details.

## Preset Examples

- `default.json`: Basic preset of a sine wave
- `ahhSynth.json`: An "Ahh" vocal using formant synthesis
- `kick.json`: A simple kick drum

## Contributing

To add a new preset:

1. Create a JSON file in `presets/`
2. Add it to the "Preset Examples" section
3. Submit a pull request

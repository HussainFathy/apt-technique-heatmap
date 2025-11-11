# APT Techniques Heatmap (MITRE ATT&CK)

This repository contains heatmaps visualizing the techniques used by different APT (Advanced Persistent Threat) groups based on the MITRE ATT&CK framework.

## Layers Included
- **Enterprise ATT&CK**: Techniques used by APT groups targeting enterprise environments.
- **Mobile ATT&CK**: Techniques used by APT groups targeting mobile devices.
- **ICS ATT&CK**: Techniques used by APT groups targeting Industrial Control Systems (ICS).

These heatmaps are generated from MITRE ATT&CK's publicly available data and reflect the frequency of techniques used by different APT groups across the three domains.

## Files
- **`combined_apt_heatmap.json`**: Contains the combined heatmap data for Enterprise, Mobile, and ICS ATT&CK layers.
- **`Enterprise_APT_Heatmap_layer.json`**: Layer data for Enterprise ATT&CK.
- **`ICS_APT_Heatmap_layer.json`**: Layer data for ICS ATT&CK.
- **`Mobile_APT_Heatmap_layer.json`**: Layer data for Mobile ATT&CK.
- **`enterprise.svg`**: Enterprise ATT&CK heatmap image.
- **`ics.svg`**: ICS ATT&CK heatmap image.
- **`mobile.svg`**: Mobile ATT&CK heatmap image.

## Usage

To view the heatmaps, you can upload the `combined_apt_heatmap.json` file to the [MITRE ATT&CK Navigator](https://mitre-attack.github.io/attack-navigator/) and explore the visualizations.

1. Go to the MITRE ATT&CK Navigator.
2. Click "Open Existing Layer" in the top right corner.
3. Upload the `combined_apt_heatmap.json` file.
4. Explore the techniques used by APT groups across the three domains: Enterprise, Mobile, and ICS.

Alternatively, you can view the combined heatmap layer directly using the following link:

[View Combined APT Heatmap in ATT&CK Navigator](https://mitre-attack.github.io/attack-navigator/#layerURL=https://raw.githubusercontent.com/HussainFathy/apt-technique-heatmap/refs/heads/main/combined_apt_heatmap.json)

## Contribution
Feel free to open issues or pull requests to contribute to the project or improve the visualizations.

# NoiseReduction_SpeechBrain-Denoising
 SpeechBrain library, implementing a conservative spectral gating approach. The provided script performs noise reduction on an audio file, leveraging the first second as a representative noise segment. 
The processed audio is then normalized for consistent amplitude. The resulting denoised and normalized audio is saved to a new file for further analysis.

Installation
bash
Copy code
pip install speechbrain
Usage
Clone the repository:
bash
Copy code
git clone https://github.com/MehvishKiani/SpeechBrain-Denoising.git
Customize the script as needed and execute it.
Workflow
Load Audio File:

Load the audio file for denoising using the SpeechBrain library.
Conservative Spectral Gating:

Implement conservative spectral gating for noise reduction.
Amplitude Normalization:

Normalize the amplitude of the denoised audio for consistent levels.
Save Processed Audio:

Save the denoised and normalized audio to a new file.
Note
Adjust parameters such as alpha for conservative spectral gating and target_rms for normalization based on specific requirements.
Directory Structure
combined/: Directory for saving processed audio files.

# pulse_preprocessing
Process waveforms to find pulses and extract pulse time, amplitude and charge. 

Generate a database with Pandas to store pulse information. 

Save dataframe to a Pickle file.

## Load waveforms

Please change the function `load_waveforms` to accomodate the format in which your waveforms are saved. 

```
def load_waveforms(directory, options=None):
  waveforms = {}
  ...
  return waveforms
```

## Basic Pulse processing

```
def analyze_waveforms(waveform):
  # For each waveform
  pulse_information = {"event_number":None, "count":None, "position":None, "amplitude":None, "area":None}
  return pulse_database
```

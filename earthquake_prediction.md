# Earthquake Prediction

## Overview
Earthquake **prediction**â€”accurately forecasting when, where, and how large an earthquake will be days to years in advanceâ€”remains one of the most elusive goals in seismology. Despite decades of research and billions of dollars invested worldwide, deterministic earthquake prediction (stating definitively that a specific earthquake will occur at a specific time and place) has never been reliably achieved. However, earthquake **forecasting**â€”estimating probabilities of earthquake occurrence over longer timescalesâ€”has progressed substantially. This module distinguishes between prediction and forecasting, reviews famous prediction attempts and why they failed, explores proposed precursors, and explains modern probabilistic approaches that are more tractable than deterministic prediction.

## Content

### Prediction vs. Forecasting: Critical Distinction

#### Deterministic Prediction
**Definition**: A statement that an earthquake of a specific magnitude will occur in a defined geographic region, time window, and magnitude range with certainty (100% probability).

**Example**: "An M6.5 earthquake will occur within 50 km of Los Angeles between January 1 and March 31, 2026."

**Status**: **No reliably successful deterministic predictions have ever been made.** Despite occasional claims and attempts, the scientific community has concluded that reliable deterministic earthquake prediction is not currently possible and may not be possible in principle.

#### Probabilistic Forecasting
**Definition**: A statement assigning a probability (between 0 and 100%, but not 100%) that an earthquake of a defined magnitude will occur in a specified region over a given time interval.

**Example**: "There is a 5% probability of an M6.5 earthquake occurring within 50 km of Los Angeles during 2026" (equivalent to roughly a 50% probability per century).

**Status**: Probabilistic forecasting is **scientifically tractable** and is the standard approach used by seismic hazard assessment agencies worldwide. These forecasts have demonstrable skill and are used for building codes and emergency preparedness.

### The Problem with Deterministic Prediction

#### Fundamental Challenges

**1. Earthquake Complexity**
- **Non-linear dynamics**: Earthquake rupture involves complex physical processes including friction, fluid pressure, and stress transfers that are inherently unpredictable on short timescales
- **Chaotic behavior**: Small changes in initial conditions can lead to very different outcomes (similar to weather prediction)
- **Multiple rupture modes**: The same fault can rupture in different ways depending on subtle conditions

**2. Precursor Ambiguity**
- **High false-alarm rate**: Potential earthquake precursors (see below) occur frequently without being followed by large earthquakes
- **Hindsight bias**: Precursors are often identified after earthquakes have occurred, making causation unclear
- **Spatial uncertainty**: Precursors may occur over a region of tens to hundreds of kilometers without indicating where exactly the earthquake will rupture
- **Temporal uncertainty**: Precursors may occur weeks to months before an earthquake (or not at all for some events)

**3. Natural Variability**
- **No two earthquakes are identical**: Recurrence intervals vary widely; clustering occurs, followed by quiescence
- **Limited earthquake samples**: Large earthquakes (M7+) occur infrequently; global earthquake catalogs with reliable magnitudes only extend back ~50â€“100 years
- **Stress transfer complexity**: Earthquakes stress nearby faults in ways that can trigger events or suppress them, depending on geometry and stress orientation
- **Incomplete understanding**: Earth's internal structure, heterogeneity, and fluid dynamics are incompletely understood

#### Statistical Argument Against Deterministic Prediction
- **Base rate problem**: Large earthquakes are rare. Even if a forecasting method is 90% accurate, the vast majority of alerts will be false alarms because earthquakes don't occur frequently
- **Reproducibility**: No forecasting method has been demonstrated to reliably predict earthquakes in blind tests (where methods are tested on future earthquakes unknown to developers)

### Failed Prediction Attempts

#### The 1975 Haicheng Earthquake "Prediction"

**Context**: In 1975, Chinese seismologists issued warnings in Haicheng that an earthquake was imminent. Hours later, a **magnitude 7.3 earthquake** struck.

**Apparent Success**:
- The prediction was hailed as a breakthrough
- An estimated 150,000 casualties were expected; only ~25,000 occurred (~2,000 deaths)
- The early alert likely saved tens of thousands of lives
- The scientific community was optimistic that deterministic prediction might be possible

**Reality**:
- **Cao Changfu**, the seismologist credited with the prediction, later admitted the warning was based primarily on **foreshocks** (small earthquakes preceding the main shock) and **superstition** rather than systematic scientific method
- Foreshocks precede only a small fraction of large earthquakes; most do not occur
- The successful prediction was largely **luck**
- When the 1976 **Tangshan earthquake (M7.5)** struck without warningâ€”in the same region with little difference in precursory activityâ€”it killed 240,000+ people
- The failure to predict Tangshan discredited deterministic prediction efforts in China

#### The Parkfield Earthquake Experiment (1985â€“Present)

**Initial Expectations**:
- Parkfield, California, is a segment of the San Andreas Fault with relatively regular earthquake recurrence
- Historical records showed earthquakes in 1857, 1881, 1901, 1922, and 1966 (roughly 20â€“25 year intervals)
- Scientists predicted the next M~6 earthquake would occur in **1988 Â± 5 years** (i.e., between 1983â€“1993)
- A dense network of seismic sensors was deployed to capture precursory signals

**The Failure**:
- **No earthquake occurred in the predicted time window**
- In **October 1992**, a magnitude 4.7 foreshock occurred, and seismologists issued a **72-hour public warning** with a 37% probability of a magnitude 6 earthquake
- The warning was a **false alarm**
- The predicted M6 earthquake finally occurred on **September 28, 2004**â€”16 years after the initially predicted window
- This represented a dramatic failure of deterministic prediction

**Lessons Learned**:
- Regular earthquake recurrence cannot be assumed
- Foreshocks alone are not reliable predictors (false alarms occur frequently)
- Earthquake clustering (deviation from regular periodicity) is common
- Public earthquake predictions can cause panic and liability issues

#### Other Failed Predictions
- **1997â€“1998 Jiang Mai, Thailand "prediction"**: Numerous predictions made; none materialized
- **Various animal behavior predictions**: In the 1980sâ€“1990s, some researchers pursued animal behavior (birds, fish, dogs) as predictors; none proved reproducible or reliable
- **Electromagnetic signals**: Some researchers claimed electromagnetic precursors; experiments have failed to validate or replicate findings

### Proposed Earthquake Precursors

Over decades, researchers have investigated numerous phenomena theorized to precede earthquakes. None have proven to be reliable, but they remain areas of ongoing research:

#### 1. Foreshocks
- **Definition**: Smaller earthquakes that precede a larger mainshock
- **Frequency**: Only ~5â€“10% of large earthquakes are preceded by foreshocks in the hours to days before
- **Problem**: Aftershocks of previous events look identical to foreshocks; distinguishing is impossible in advance
- **Reliability**: Very low; millions of small earthquakes occur without leading to large events

#### 2. Radon Gas Emissions
- **Basis**: Radon gas is released when crustal rocks are strained and fracture
- **Observations**: Anomalous radon concentrations have been reported before some earthquakes:
  - 1978 Izu-Oshima earthquake: Groundwater radon decreased 3 months before, with sharp drop 5 days before
  - 1995 Kobe earthquake: Groundwater radon increased months before, peaked 9 days before
  - 2011 TÅhoku earthquake: Atmospheric radon anomalies detected ~3 months before
- **Problem**:
  - Radon concentrations are affected by weather, water table changes, soil moisture, atmospheric pressure
  - Many anomalies are not followed by earthquakes
  - Monitoring would require dense network of hundreds of detectors
  - Cost and maintenance challenges are substantial

#### 3. Groundwater Changes
- **Observations**: Water levels and temperatures have changed prior to some earthquakes
- **Mechanism**: Proposed that crustal strain opens fractures, changing water circulation
- **Problem**: Groundwater responds to many factors (rainfall, seasons, human activity); distinguishing earthquake-related changes from background noise is difficult

#### 4. Animal Behavior
- **Historical reports**: Animals behaving unusually before earthquakes (birds flying erratically, fish jumping, dogs barking)
- **Anecdotal evidence**: Individual cases documented after earthquakes occur
- **Problem**:
  - **Hindsight bias**: After an earthquake, observers remember unusual animal behavior that occurred beforehand
  - **Confirmation bias**: Unusual animal behavior is common; most does not precede earthquakes
  - **No reproducible mechanism**: How animals would sense impending earthquakes is unclear
  - **Laboratory tests**: Attempts to train animals to respond to earthquake-like stimuli have failed to demonstrate precursor sensing
  - **Scientific consensus**: Animal behavior is not accepted as a reliable earthquake precursor

#### 5. Electromagnetic Signals
- **Observations**: Some researchers report electromagnetic anomalies (ULF, ELF, VLF signals) prior to earthquakes
- **Proposed mechanism**: Crustal strain generating electrical fields
- **Problem**:
  - **Difficulty distinguishing signals**: Electromagnetic noise from power lines, communications, solar activity complicates analysis
  - **No reproducibility**: Results cannot be consistently replicated
  - **Theoretical uncertainty**: Physical mechanism for electromagnetic precursors is not well-established
  - **Limited operational use**: Despite decades of research, electromagnetic precursors are not used operationally anywhere

#### 6. Creep Events (Slow-Slip Events)
- **Observations**: Some faults exhibit episodic slow-slip (sometimes called "silent earthquakes") during which the fault moves gradually over days to weeks without generating typical earthquake shaking
- **Relevance**: Slow-slip events may relieve stress, potentially delaying or triggering subsequent large earthquakes
- **Problem**: Effects are complex and location-specific; predicting when slow-slip will trigger an earthquake remains elusive
- **Current use**: Monitored and studied for research, but not used operationally for earthquake prediction

### Modern Probabilistic Approaches

#### Earthquake Forecasting Based on Statistical Models

Rather than attempting deterministic prediction, modern seismology uses **probabilistic approaches** that are scientifically tractable and provide useful information:

#### 1. Long-Term Forecasting (Decades to Centuries)
Uses models based on fault recurrence intervals:

**Characteristic Earthquake Model**:
- Assumes faults rupture in similar magnitude events at roughly regular intervals
- Uses historical records and paleoseismic evidence to estimate recurrence times
- Calculates probability that the next event will occur in a given time window
- **Example**: Alpine Fault in New Zealand; last rupture 1717; recurrence interval ~200â€“300 years; probability of M8+ by 2068 is ~75%

**Renewal Models** (Brownian Passage Time, Lognormal):
- More sophisticated models accounting for variability in recurrence intervals
- Use time since last event, mean recurrence interval, and measured variability
- Provide probabilistic forecasts over decades to centuries

#### 2. Short-Term Forecasting (Days to Weeks)

**Epidemic Type Aftershock Sequence (ETAS) Model**:
- Statistical model of earthquake clustering
- Accounts for fact that earthquakes are not randomly distributed; they cluster in space and time
- Uses historical seismicity patterns to forecast increased probability following large earthquakes
- Tracks decay of aftershock activity according to Omori-Utsu law (aftershock rate decreases with time raised to negative power)
- Can be updated with real-time earthquake data

**Stress Transfer Models**:
- Earthquake ruptures change stress on nearby faults
- If stress is increased (Coulomb stress transfer), subsequent earthquakes become more likely
- If stress is decreased (stress shadow), subsequent earthquakes become less likely
- Helps understand earthquake triggering and clustering

#### 3. Seismic Gap Hypothesis

**Concept**: Segments of major faults that have not ruptured recently are "seismic gaps" where stress is accumulating

**Application**: Identify regions of elevated earthquake risk

**Examples**:
- Miyagi-Oki gap (Japan): Subduction zone segment where no M7+ earthquake had occurred since 1897; in 2011, the M9.1 TÅhoku earthquake partly ruptured this gap
- Shumagin Gap (Alaska): No M8+ earthquake since at least 1903; considered high-risk for future rupture
- Istanbul Gap (Turkey): Sea of Marmara segment of North Anatolian Fault; no large rupture since 1766; high-risk region

**Limitation**: Gaps don't always rupture when expected; rupture timing remains uncertain

### Induced Seismicity Forecasting

Modern research is exploring forecasting of **induced earthquakes**â€”those triggered by human activities:

#### Mechanisms
- **Hydraulic Fracturing (Fracking)**: Pressurized fluid injects into shale formations to extract oil/gas; can trigger earthquakes
- **Geothermal Energy**: Enhanced geothermal systems use pressurized water to create permeability; can trigger earthquakes
- **Reservoir Impounding**: Filling large dams increases water pressure on underlying rocks; can trigger earthquakes
- **Wastewater Injection**: Disposal of oil/gas production wastewater in deep wells increases subsurface pressure

#### Forecasting Approach
- Model where induced earthquakes are likely based on fluid injection patterns and geology
- Probabilistic forecasts of magnitude and frequency
- More tractable than natural earthquake prediction because the triggering mechanism is better understood and controllable

### Current Scientific Consensus

#### International Commission on Earthquake Forecasting (2009 Report)
- **Deterministic Earthquake Prediction**: "Reliable and skillful deterministic earthquake prediction is not yet possible" and "is not expected in the foreseeable future"
- **Probabilistic Forecasting**: "The best operational strategy is to accelerate the development of probabilistic earthquake forecasting"
- **Precursors**: "We are not optimistic that diagnostic precursors will provide an operational basis for deterministic earthquake prediction in the near future"

#### Current Operational Practice
- **Building Codes**: Based on long-term probabilistic forecasts
- **Insurance**: Uses probabilistic seismic hazard assessments
- **Emergency Planning**: Based on probabilistic estimates of earthquake likelihood
- **Research Focus**: Continues toward improving understanding of earthquake physics and precursors, but with realistic expectations about predictability

### The Fundamental Reason: Earthquake Mechanics

Earthquakes are governed by **complex, chaotic dynamics** involving:
- **Nonlinear friction**: Frictional resistance depends on slip rate, temperature, and pressure in complicated ways
- **Fluid-solid coupling**: Pore fluid pressure affects effective stress on faults
- **Heterogeneity**: Real faults have variations in geometry, material properties, and stress that affect rupture
- **Multiple length scales**: Fault roughness and complexity operates across millimeter to kilometer scales
- **Coupling to other systems**: Stress transfer, thermal effects, and chemical reactions complicate rupture nucleation

These factors create a system where small perturbations can lead to dramatically different outcomesâ€”the hallmark of chaotic systems where long-term deterministic prediction is impossible.

## Related Topics
- [seismic_monitoring]
- [earthquake_early_warning]
- [earthquake_measurement]
- [fault_types]
- [seismology_basics]

## References
- IASPEI (International Association of Seismology and Physics of the Earth's Interior): Operational Earthquake Forecasting Report (2009)
- USGS: Earthquake Prediction
- Geological Society of America: The Prediction Problems of Earthquake System Science
- Nature: Detection of Atmospheric Radon Concentration Anomalies
- Physics World: A Radon Detector for Earthquake Prediction
- Nautilus Magazine: The Last of the Earthquake Predictors
- Earth Magazine: Earthquake Predictionâ€”Gone and Back Again
- Project Euclid: Testing Earthquake Predictions (Statistical Framework)
- Journal of the Seismological Society of America: The Earthquake Prediction Experiment at Parkfield
- arXiv: Benchmark Datasets for Earthquake Forecasting with Neural Point Processes
- NSF: Question-Driven Ensembles of Flexible ETAS Models

---
**Keywords**: prediction, forecasting, probabilistic, deterministic, precursor, Haicheng, Parkfield, ETAS, seismic gap, foreshock, radon, induced seismicity

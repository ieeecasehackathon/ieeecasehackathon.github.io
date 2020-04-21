
# ASME HACKATHON on Computers and Information in Engineering (ASME IDETC/CIE 2020)

*2020 ASME-CIE Hackathon: Identifying, Extracting, Analyzing of Value from Large Unstructured Data Sets in Mechanical Engineering*
*Hilton, St. Louis, MO, USA*
*August 15-16, 2020*

In conjunction with ASME IDETC/CIE 2020

Sponsored by

ASME Computers & Information in Engineering Division (CIE) &

ASME Technical Events and Content (TEC) Sector Council

ASME Manufacturing Engineering Division (MED) Centennial Celebration Endorsed Event

[Click to Register for the Hackathon](https://event.asme.org/IDETC-CIE/Program/Hackathon)

($25 for Hackathon event only; [Travel Awards Available](https://event.asme.org/Events/media/library/resources/idetc-cie/IDETC2020-TravelAwardApplicationProcess.pdf).)
 
Meeting Location: Room Name, Hilton, St. Louis, MO




Participants can find relevant information the [official ASME website](https://event.asme.org/IDETC-CIE/Program/Hackathon) (https://event.asme.org/IDETC-CIE/Program/Hackathon) and [GitHub website](https://asmehackathon2020.github.io/) for this repository. 







## Awards

* First Place: $2000
* Second Place: $1000
* Third Place: $500


## Organizers/Mentors

1. Dr. Christopher McComb (Pennsylvania State University) -- Assistant Professor.

2. Dr. Zhenghui Sha (University of Arkansas) -- Assistant Professor

3. Dr. Faez Ahmed (MIT) -- Assistant Professor

4. Dr. Yan Lu (NIST) -- Senior Research Scientist

5. Dehao Liu (Gatech) -- Ph.D. Candidate

6. Dr. Anh Tran (Sandia National Laboratories) -- Postdoctoral Appointee

## Important dates

* ***May 21st, 2020***: Deadline for hackathon sign-up
* ***August 15th, 3 pm 2020***: Hackathon Kick-off
* ***August 16th, 4 pm 2020***: Due for Hackathon deliverables
* ***August 16th, 8 pm 2020***: Awarding ceremony

# Introduction

This 2020 ASME-CIE Hackathon is co-located with the International Design Engineering Technical Conferences & Computers and Information in Engineering Conference. The Hackathon is sponsored by the ASME Technical Events and Content (TEC) Sector Council and the ASME Computers & Information in Engineering Division (CIE) with the goal to build multi-stakeholder (society-university-industry) relations and impact the quality and quantity of data-skilled mechanical engineers. The ASME-CIE 2020 Hackathon is the first Hackathon event held by ASME and is expected to become one of the signature events of the American Society of Mechanical Engineering (ASME).

#### Theme

Big Data is defined as “large volumes of high velocity, complex and variable data that require advanced techniques and technologies to enable the capture, storage, distribution, management, and analysis of the information.” However, it is reported that majority of the data collected (more than 80%) is unstructured data in the form of image, video, audio, undefined text and numbers. This is true in many mechanical engineering subfields where sensors are ubiquitous and digitization is pervasive, for example, when analyzing Amazon reviews to elicit customer preferences in support of engineering design, and using images of 3D printing in support of manufacturing prognosis. While the value of unstructured data is evident by the vigor and velocity with which new tools are being created in the private sector to extract this hidden value, in mechanical engineering, the question of how to leverage the power of unstructured data to benefit product design and development, manufacturing and complex systems engineering is still yet fully answer.

The ASME-CIE Hackathon attempts to provide an open mechanism for researchers to explore new statistical and machine-learning techniques appropriate for the use of unstructured text, images, audio etc. in design, manufacturing and systems engineering, and on the other hand, to develop new educational pathways to train the next generation of data-skilled mechanical engineers. The participants will have the opportunity to learn and experience various data visualization, data mining, and machine learning methods to develop automated processes for:

* Identification of patterns within the unstructured data that are predictive of valuable or negative attributes.
* Use of valuable extracted content to improve predictive models.
* Removal or correction of negative content associated with errors, bias, or privacy.

Hackathon problems can be found in [this PDF](https://event.asme.org/Events/media/library/resources/idetc-cie/IDETC-Hackathon-Problems.pdf).

#### Teamwork

Hackathon is a teamwork. You do not need to have all the skills – that’s what TEAMWORK is for! Please join us if you have:

* Creative or innovative ideas
* Business or marketing talents
* Data science or statistics concepts
* Domain knowledge and critical thinking
* Computational linguistics skills
* Programming skills

 
#### Hackathon Team and Presentation

* All participants must be registered via here. Register the event and attend the Hackathon physically. Each participant brings his/her own laptop with all the necessary computing tools. Everyone will be placed in a team up to three members. You may form your own team onsite. All implementation must be based on the original work.
* Each Hackathon team will continue their own meetings and hacking exercises during the two days between 4pm 08/15/20 and 4pm 08/16/20.
* Each team needs to present their teamwork including the technical approach and the results.

## Hackathon Problem 1: Machine Damage Accumulation Prediction using Heterogeneous Temporal Sensor Data

##### Subject Matter Expert
* *Christopher McComb, Assistant Professor, School of Engineering Design, Technology and Professional Programs, PennState*
* *Zhenghui Sha, Assistant Professor, Department of Mechanical Engineering, University of Arkansas*
* *Faez Ahmed, Postdoctoral Fellow, Department of Mechanical Engineering, Northwestern University*

#### Problem Statement

The Bernard M. Gordon Learning Factory is a hands-on facility for engineering students, which provides modern design, prototyping, and manufacturing facilities. Many of the machines in the Learning Factory are instrumented using a sensor suite that provides monitoring capabilities. The readings from a heterogeneous set of sensors is used to report metrics continuously for many different machines. 

The objective of this problem is to forecast future usage patterns for five commonly used machines in the learning factory with a time resolution of 10 minutes. Machine usage, here, is a binary variable where a true value indicates that a machine will be used at some point during a future 10 minute interval, and a false value indicates that the machine will not be used during that interval. Specifically, teams should train algorithms that are capable of predicting usage for up to 2 hours in the future: 12 binary values per machine, each representing whether or not the machine will be used in successive 10-minute intervals.

#### Challenges

This data and use case present several challenges. These include:
* Is it feasible to construct a data-driven digital twin for forecasting? ([Kunath et al., 2018](#RefsProblem1)) 
* What is the best approach to identifying appropriate signals in this data with which to make predictions? ([Long et al., 2019](#RefsProblem1))
* The data provided here represents only the technical side of the system, but is heavily impacted by the human use of the learning factory as well. ([Smith et al., 2013](#RefsProblem1)).
* What is an appropriate threshold on measured sensor values to indicate active use of the machine? ([Yan et al., 2017](#RefsProblem1))

#### <a name="RefsProblem1"></a> References

1. Kunath, M., & Winkler, H. (2018). Integrating the Digital Twin of the manufacturing system into a decision support system for improving the order management process. Procedia CIRP, 72, 225-231.
2. Long, Wen, Zhichen Lu, and Lingxiao Cui. "Deep learning-based feature engineering for stock price movement prediction." Knowledge-Based Systems 164 (2019): 163-173.
3. Smith, A., Hielscher, S., Dickel, S., Soderberg, J., & van Oost, E. (2013). Grassroots digital fabrication and makerspaces: Reconfiguring, relocating and recalibrating innovation?. University of Sussex, SPRU Working Paper SWPS, 2.
4. Yan, J., Meng, Y., Lu, L., & Li, L. (2017). Industrial big data in an industry 4.0 environment: Challenges, schemes, and applications for predictive maintenance. IEEE Access, 5, 23484-23491.

## Hackathon Problem 2: Smart Manufacturing – In-Process Data Mining for Powder-Bed Fusion Additive Manufacturing

##### Subject Matter Expert
* **Yan Lu, Senior Research Scientist, Professor, System Integration Division, NIST**
* **Dehao Liu, School of Mechanical Engineering, Graduate Research Assistant, George Institute of Technology**
* **Anh Tran, Postdoctoral Appointee, Sandia National Laboratories**

#### Problem Statement

Additive manufacturing (AM) processes build parts layer-by-layer directly from 3D models. AM enables the fabrication of complex heterogeneous parts, which makes it an attractive alternative for high-value, low-volume production. However, the turnkey deployment of the technology hits consistent barriers including low part repeatability and lack of effective qualification tools. Fundamental issues exist with the understanding and control of the dynamic and stochastic nature of AM processes. In-situ monitoring for additive manufacturing is considered as the main enablers to understand AM processes, set optimal material and machine specific process parameters, and close the control loops in real-time to limit the stochastic variability introduced by the dynamic nature of the processes. For manufacturers to build quality AM parts, in-situ data has the potential to be used for quality assurance and certification, which will dramatically reduce the need of lengthy and high-cost post inspections. 

The goal of this hackathon subtopic is to promote the use of data science in powder-bed fusion additive manufacturing to accelerate the understanding of powder-bed fusion AM process, to improve PBF process monitoring and control as well as to explore in-process data-based product qualification. This will be achieved by developing sets of data analytics tools, predictive models, and process control and optimization algorithms for PBF processes. This tool will be an early step in allowing industry to move away from 100% testing and towards born-qualified parts.

#### Challenges

* AM in-process data registration – how to align the multi-modal in-process monitoring data in time and space to allow for fusion and correlation ([Argyriou et al. 2015](#RefsProblem2)).
* What kind of features to be extracted from the multi-level, multi scale AM in-process monitoring data, e.g., build command, chamber monitoring trended data, co-axial images and layerwise images etc. 
* What kind of relationship between build commands and the in-process measurements such as coaxial melt pool characteristics/layerwise surface images. ([Yang et al. 2019a](#RefsProblem2), [Yang et al. 2019b](#RefsProblem2))
* How to fusion the data from the multi-modal in-process measurements ([Castanedo 2013](#RefsProblem2))
* How to develop real-time control or layerwise control strategy from the data for the PBF AM processes? ([Mani 2015](#RefsProblem2))

#### Datasets

An experimental L-PBF build was conducted on the Additive Manufacturing Metrology Testbed (AMMT) at National Institute of Standards and Technology (NIST). The AMMT is a fully customized metrology instrument that enables flexible control and measurement of the L-PBF process. Two cameras were installed for process monitoring, including a high-resolution camera that captures the layerwise images of the entire part, and a high-speed camera used to capture melt pool images. The Galvo mirror system and the beam splitter allow the high-speed camera to focus on current laser melting spot. Emitted light from the melt pool, through a 850 nm bandpass filter (40 nm bandwidth), is imaged on the camera sensor. On AMMT both Galvo and laser command are updated on field programmable gate array (FPGA) at 100 KHz. The digital commands are developed to specify the motion of the Galvo scanner of the L-PBF system. It is transformed into a time series of scanner positions and laser power as control commands.

Inconel 625 powder and build plate were used. The substrate has a dimension of 102 mm x 102 mm x 13 mm. Twelve rectangular parts (with chamfered corners) of dimensions 10 mm x 10 mm x 5 mm were laid on the substrate, with a minimum spacing of 10 mm between parts. Each part was built with a different scan strategy.

Data sets and data formats used for the study include:
1. Part Design model (.stl file)
2. Part layout (drawing in pdf/part location in xml)
3. Process settings; camera settings; and camera calibration models (PNG, jpg, xml)
4. Data sets for build command at 100KHz for every part every layer (xls)
5. Melt-pool images for every part, every layer at 2KHz (bmp/jpg/avi/PNG)
6. Layerwise images, 2 per layer, before and after exposure settings (bmp/PNG)

#### <a name="RefsProblem2"></a> References

1. Vasileios Argyriou, Jesús Martínez Del Rincón, Barbara Villarini, Alexis Roche, “Image, Video & 3d Data Registration”, John Wiley & Sons, 2015.
2. Guyon, I., Gunn, S., Nikravesh, M., Zadeh, L.A. (Eds.), Feature Extraction-Foundations and Applications,  Springer, 2006.
3. Yang, Z., Lu, Y., Yeung, H., and Krishnamurty, S., “From Scan Strategy to Melt Pool Prediction: A Neighboring-Effect Modeling Method”, CIE 2019.
4. Yang, Z., Lu, Y., Yeung, H., and Krishnamurty, S., “Investigation of Deep Learning for Real-Time Melt Pool Classification in Additive Manufacturing.
5. Federico Castanedo, “A Review of Data Fusion Techniques”, The Scientific World Journal Volume 2013.
6. Mani, M., Lane, B. M., Donmez, A. M., Feng, S. C., Moylan, S. P., Fesperman, R. R., “Measurement Science Needs for Real-time Control of Additive Manufacturing PowderBed Fusion Processes”, NISTIR 8036, 2015. 

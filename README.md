# Ultrasonic-based distance detector
In the following repo a brief explanation on the design, test and development of a simple distance detector based on ultrasonic transducers is provided. This project was carried on along with a professor from the Polytechnic University of Catalonia, as an improvement of an Analog Circuits subject's laboratory design.

![Overall schematic description of the device.](esquematico_detector_distancia_pic.jpg)

The device's principle of foundation lies on deriving the distance at which we're pointing to as a function of the time elapsed between an emission and detection of a signal. Further detail is properly provided in an specific section.

The design consists of two main units. First, an **excitation phase** in which a burst-like square signal is generated using a microcontroller in order to send periodical signals from a transducer transmisor. Second, an **acconditioning and processing** phase is required to determine whether a detection has taken place on the reciever transducer. The latter usually implies an amplification phase, as we will analyze, and at the very end a comparator module to translate the information into a binary format.

## Excitation phase

## Acconditioning phase

## Detection principle and implementation
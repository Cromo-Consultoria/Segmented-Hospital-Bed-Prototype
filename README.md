# Segmented-Hospital-Bed-Prototype
This code is supposed to be used with a Segmented Hospital Bed that weighs different parts of the body at the same time.

The code connects to an electronic wheighing scale via a serial port, specifically COM3, with the purpose of obtaining weight readings. It reads these values, calibrates the data using specific calibration factors and an inclination angle provided by the user, and then saves this information in a CSV file called "dados_balanca.csv."

In addition to the weight readings, the code calculates the weight distribution across different parts of the body, such as arms, torso, and legs, using proportion factors specific to each body part. These calculations are based on the readings obtained and the scale's settings. The resulting information is organized and also saved in the CSV file.

The code also includes logging mechanisms to monitor and record important events and errors during execution. It is designed to handle potential serial port connection failures, logging errors and safely terminating the program if necessary.

In summary, the code is responsible for automating the collection, calibration, and storage of data from a scale, as well as performing additional calculations to obtain the weight distribution across different parts of the body, all in a structured and efficient manner.

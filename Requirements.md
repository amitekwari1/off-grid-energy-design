<font size="5"> <center> ELP305 Design and Systems Laboratory </center> </font>
<font size="4"> <center> Semester 2, 2021-2022 </center></font>
<font size="3"> <center> Tribe E </center></font>

# 1. **SUNERGY Requirements**

In the following document, we give a brief on various traits that our off-grid living solution must possess. We also jot down the various requirements that will be needed to ensure our proposed solution is as efficient and trust worthy as possible.

<font size="4">**Table of Contents:**</font>

-   [1. **SUNERGY Requirements**](#1-sunergy-requirements)
    -   [1.1 **Base Setup**](#11-base-setup)
    -   [1.2 **Basic Requirements**](#12-basic-requirements)
    -   [1.3 **Technical Requirements**](#13-technical-requirements)
    -   [1.4 **References**](#References)
    -   [1.5 **Documentation Statistics**](#14-documentation-statistics)
    -   [1.6 **Document Readability indices**](#15-document-readability-indices)

## 1.1 **Base Setup**

One of the main requirements for the system is that it is reasonably easy to set up so that minimum technical assistance is required for the same, and the house owner can perhaps even set it up himself.
These requirements require the system to be:

-   **Easy to implement**: The system should be easy to implement so that any person with little or no technical experience can implement and install the system by following simple instructions. The system also needs to be easy to repair so that there are minimum power cuts.
-   **Low maintenance**: The system needs to require low maintenance so that the user does not have to get it serviced frequently. If possible, it should be such that the users can themselves service it.
-   **Set-up time**: The system should be able to be set up within a short duration of time (3-4 days) to avoid any inconvenience in the form of power breaks to the users during the setup.
-   **Easy to Remove**: The system should be easy to remove so that the user can remove the setup if they want to relocate to a new location. For this, the system should also allow easy transportation over long distances so that the user can take it with themselves
-   **Long-term sustenance**: Should sustain itself for long periods of time even in the absence of production (no solar production during winters).
-   **Backup Generator**: Need in cases of emergency, high power usage situations, and 2nd option for achieving the above goal (long-term sustenance).

## 1.2 **Basic Requirements**

Some of the basic user requirements are:

1. **Accommodation**: The energy generated should be able to satisfy the needs of a family of six.

2. **Power Requirements**: The daily power requirement is approximately 24-25 kWh. The explanation for the same can be seen as follows:
 <p style="page-break-before: always">

| S. No.                  | Appliance                 | Number of Appliances | Power Consumed by Each | Daily Time Consumption | Total Energy Consumed  | Explanation                                                       |
| ----------------------- | ------------------------- | -------------------- | ---------------------- | ---------------------- | ---------------------- | ----------------------------------------------------------------- |
| 1                       | Tube Light                | 10                   | 0.036kW                | 8 Hours                | 0.036\*5\*8=1.44kWh    | Assuming, on average, 5 lights out of 10 are ON for 8 hours.      |
| 2                       | Television (50 inches)    | 1                    | 0.1kW                  | 6 Hours                | 0.1\*1\*6=0.6kWh       | Assuming the television to be ON for 6 hours a day                |
| 3                       | Air Conditioner (1 tonne) | 1                    | 1kW                    | 8 Hours                | 1\*1\*8=8kWh           | The ACs need to be used only during the summers                   |
| 4                       | Heater                    | 1                    | 1.5kW                  | 6 Hours                | 1.5\*1\*6=9kWh         | The heater needs to be used only during the winters.              |
| 5                       | Ordinary ceiling fan      | 4                    | 0.075kW                | 10 Hours               | 0.075\*4\*10=3kWh      |                                                                   |
| 6                       | Refrigerator (400L)       | 1                    | 0.15kW                 | 24 Hours               | 0.15\*1\*24=3.6kWh     |                                                                   |
| 7                       | Washing machine (7kg)     | 1                    | 2kW                    | 0.5 Hour               | 2\*1\*0.5=1kWh         |                                                                   |
| 8                       | Water Heater              | 2                    | 1.5kW                  | 1 Hour                 | 1.5\*2\*1=3kWh         |                                                                   |
| 9                       | Personal Computer         | 1                    | 0.2kW                  | 6 Hours                | 0.2\*1\*6=1.2kWh       |                                                                   |
| 10                      | Miscellaneous             |                      |                        |                        | 3kWh                   | Assuming laptops, cooking appliances etc to consume 3kWh per day. |
| Daily power requirement | Summers//Winters          |                      |                        |                        | 21.84//22.84 kWh ± 10% |

3. **Budget**: The cost of manufacturing should not be more than Rs. 4,00,000.

4. **Backup**: In case of any system failure, there must be a fuel generator strong enough to provide backup for the basic energy requirements.

5. **Water Requirements**: The energy should sustain the operation of bore pumps to satisfy the water requirements of the house.

6. **Season**: There should be suitable alternatives to meet the energy requirements with changing seasons such as substitutes for solar panels during the winter season.

7. **Maintenance**: The system should require low maintenance in terms of system longevity. This should also be easy-to-handle by the residents themselves.

8. **Efficiency**: The batteries used to store energy should be efficient in order to ensure longer periods of usage. The appliances can also be used in an energy saver mode.

9. **Safety**: There must be fuses and master controller or circuit breakers (MCB) in order to ensure safety in case of fluctuations or malfunction.

10. **Monitoring**: The system should have a provision for monitoring the total energy consumed by all major appliances.

11. **Remote Access**: The system should be equipped with a remote accessing facility of solar panels as well as the appliances.

## 1.3 **Technical Requirements**

Various technical apparatus and tools required to acheive our goal are:

1. **Solar Panels**: An assembly of photo-voltaic cells mounted and connected to each other used to harness solar energy and convert it into electrical energy. The electricity produced by solar panels is DC in nature. Some factors characteristic of a good solar panel are low price, high efficiency, low-temperature coefficient.

2. **Batteries**: Deep cycle batteries are used in order to store energy produced by the solar panels during the day to use during the night. In order to have a long battery life, we wish to have a battery with a larger number of charge/recharge cycles.

3. **Inverter**: Solar panels generate DC electricity which needs to be converted to AC electricity needed by many common household appliances which are achieved by using an inverter. We wish to have an inverter that is cheap and provides high efficiency in converting DC to AC with minimal power losses.

4. **Timed rotators for panels** (optional): In order to obtain more solar energy, the panels should be able to rotate on a shaft in accordance with the motion of the sun. The cost of such a tracking-based system, however, can be significant.

5. **Mounting apparatus**: Solar panels are usually connected to each other and then subsequently mounted either on the roof or on the ground. The panels must be mounted so as to ensure cooling airflow and in a manner where maximum sunlight is available to the panels throughout the day.

6. **Charge Controllers**: Charge controllers are used to control the amount of current fed into the battery by the solar panels.This ensures the batteries are not overcharged during the day and don't leak current back to the panels during the night. There are two types of charge controller devices available - PWM and MPPT of which MPPT though more expensive is upto 30% more efficient than PWM charge controllers.

7. **Battery Monitor**: This meter would allow us to get an idea of how much power is being generated, how much amount we are saving by using solar panels and helps monitor which appliances use more power to manage energy utility.

8. **Backup Generator**: In case of off-grid systems backup power supply like a generator can serve as an alternate power supply in case of cloudy days, high demand or other unforeseen circumstances. The environmental impact of the generator could be reduced by using alternative fuels like biodiesel.

9. **Disconnects**: These are manual switches that enable us to cut off the power supply to and from the inverter in case of maintenance. This prevents current from flowing beyond the switch to some damaged component.

10. **PIR sensors**: Passive infrared sensors can be used in order to detect human motion in and out of rooms. This would allow us to smartly switch off electrical appliances not being used in order to save energy.

11. **Dynamo**: A small electrical generator that can be installed in gym equipment to harness energy to power some low power electrical devices

12. **Wires**: Insulated copper or aluminum wires needed to connect various electrical components

13. **Bio Gas plant**: A biogas plant can be set up to harness energy out of the biodegradable waste that is produced in the household. This can later be used in the form of cooking gas or processed through a biogas generator for an alternative electricity source.

## 1.4 **References**

-   https://www.alternative-energy-tutorials.com/solar-power/7-components-of-your-solar-power-system.html

## 1.5 **Documentation Statistics**

-   **Word count**: 1560
-   **Total number of unique words**: 647
-   **Total number of repeated words**: 913
-   **Total number of sentences**: 41
-   **Total number of characters**: 9382
-   **Total number of characters without spaces**: 7888
-   **Total number of syllables**: 2466
-   **Average number of words per sentence**: 39
-   **Average number of characters per sentence**: 229
-   **Average number of characters per word**: 5.10
-   **Average number of syllables per word**: 1.57

The above results were obtained using https://wordcounter.net/.

## 1.6 **Document Readability indices**

-   **Flesch Reading Ease score**: 57
-   **Dale-Chall Readability score**: 12
-   **Flesch-Kincaid Grade level**: 9
-   **The Coleman-Liau Index**: 11
-   **Automated Readability Index**: 10
-   **SMOG Formula score**: 13
-   **Spache Readability score**: 6

The above scores were obtained using Visual Studio Code extension called Readability Check by jemcclin.

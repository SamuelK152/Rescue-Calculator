# Rescue Stop Calculator v2.3

https://samuelk152.github.io/Rescue-Calculator/

A calculator designed to be used by Amazon dispatchers to estimate a driver's progress and determine if a rescue is needed.

## Overview

The Rescue Stop Calculator is a web-based tool that helps Amazon dispatchers quickly estimate whether a delivery driver will complete their remaining stops before a required return time. By entering the number of stops left, the driver's average stops per hour (SPH) or average time per stop, and the required return time, dispatchers can:

- **Estimate the driver's finish time**
- **See if the driver will return on time**
- **Calculate how much time can be spent at each stop to finish on time**
- **Determine how many stops the driver can complete before the required return**
- **Identify how many stops may need to be rescued**

# NEW

### Advanced Options & Improvements (v2.3)

- **Advanced Options:** Toggle a two-rate calculation for drivers who change pace mid-route. Enter stops before rate change and the new rate to get more accurate finish/rescue estimates.
- **Sum Input for Additional Time:** The "Additional Time (min)" field now accepts sums (i.e., `15 + 20 + 30`) for quick entry of multiple non-delivery time segments.
- **Improved Calculation Logic:** The calculator now handles advanced scenarios, including split rates and dynamic rescue calculations, with clearer results and bar visualization.
- **Code Comments & Cleanup:** The codebase is now easier to read and maintain, with clear comments for each section and improved formatting.

## Features

- Simple, mobile-friendly interface
- Enter stops, SPH, or time per stop (auto-converts between SPH and time/stop)
- Advanced options to calculate return times of drivers who change pace mid-route
- Optional field for additional time (Breaks, return drive time etc.)
- Selectable required return time
- Instant calculation and clear results
- Feedback link for

## How to Use

1. **Enter Remaining Stops:**  
   Input the number of stops the driver has left on their route.

2. **Enter Driver's Avg SPH or Avg Time/Stop:**

   - Enter the driver's average stops per hour (SPH), or
   - Enter the average time per stop (in minutes).  
     The calculator will automatically update the other field for you.

3. **Enter Return Drive Time (optional):**  
   If the driver has a non-delivery drive time (e.g., returning to the station), enter it in minutes.

4. **Select Required Return Time:**  
   Choose the time by which the driver must return.

5. **Click "Calculate":**  
   The calculator will display:
   - Whether the driver will finish by the desired time
     If not,
   - How many stops are possible before OT
   - How many stops are needed to be rescued before OT
   - The estimated finish time
   - The maximum allowable time per stop in order to finish on time
   - The average stops per hour required in order to finish on time

## Example

If a driver has 30 stops left, averages 18 SPH, and must return by 8:15 PM, the calculator will estimate their finish time and indicate if a rescue is needed.

## Feedback

For feedback or suggestions, click the "FeedBack" link at the bottom of the calculator or

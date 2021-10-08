.. container::

   ============= ===============
   clemson_temps R Documentation
   ============= ===============

   .. rubric:: Daily Clemson Temperature Data
      :name: daily-clemson-temperature-data

   .. rubric:: Description
      :name: description

   This data set contains daily temperatures (highs) for Clemson, South
   Carolina from Jan. 1, 1930 to the end of the most recent calendar
   year. The goal is to update this periodically with new data for as
   long as I live in this town.

   .. rubric:: Usage
      :name: usage

   ::

      clemson_temps

   .. rubric:: Format
      :name: format

   A data frame with 32,777 observations on the following 8 variables.

   ``date``
      the date

   ``year``
      the year

   ``month``
      the month

   ``day``
      the day of the month

   ``yd``
      the day of the year

   ``value``
      the daily high in Celsius*10. I don't know why NOAA does it this
      way, but there you go.

   ``tmax``
      the daily high, adjusted to Fahrenheit

   .. rubric:: Details
      :name: details

   Data obtained from NOAA, via the rnoaa package. The station
   identifier is ``GHCND:USC00381770`` for added context.

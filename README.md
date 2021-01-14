# Find slots

### Usage

  Set environment

  ```
  make env
  ```

  Launch

  ```
  make
  ```
  Launch in background

  ```
  make hide
  ```

### Explained

Once a slot is found you will be redirected to the slot page

### Problem

Slots are in javascript code not in static HTML code. MechanicalSoup gives access to static HTML code, which is not enough to find the slots. Selenium allows crawling the content that has been added through javascript. To find slots this is necessary.

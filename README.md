# 42-webscraper-slot-finder

Using python web-scraping to find 42 school project correction slots.

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

Once a slot is found you will be redirected to the slot page.

### Problem

Slots are in javascript code not in static HTML code. **MechanicalSoup** gives access to **static HTML** code, which is not enough to find the slots. **Selenium** allows crawling the content that has been added through **javascript**. To find slots this is necessary.

### Next
Final functional version using Selenium is found in [Artygo8/42SLOT_FINDER](https://github.com/Artygo8/42SLOT_FINDER) project.

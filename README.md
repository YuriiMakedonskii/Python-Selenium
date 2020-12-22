# Python-Selenium
# This is a sample Python script.

# Press Shift+F10 to execute it or replace it with your code.
# Press Double Shift to search everywhere for classes, files, tool windows, actions, and settings.


def print_hi(name):
    # Use a breakpoint in the code line below to debug your script.
    print(f'Hi, {name}')  # Press Ctrl+F8 to toggle the breakpoint.


# Press the green button in the gutter to run the script.
if __name__ == '__main__':
    print_hi('PyCharm')

# See PyCharm help at https://www.jetbrains.com/help/pycharm/
from selenium import webdriver
from selenium.webdriver.support.select import Select
import xlsxwriter
import time
import pandas as pd
import re
browser = webdriver.Chrome()
browser.maximize_window()
browser.get('https://netpeak.ua/')
Select (browser.find_element_by_xpath (html/body/div[3])) . select.by_visible_text
Select (browser.find_element_by_xpath (html/body/div[2]/h1)).select.by_visible_text
Select (browser.find_element_by_xpath (*[id=="user-main-info"]/div[8]/div[1]/div[4])).select.by_visible_text
time.sleep(10)
writer.save()
print('Я всё!', date)
driver.close()

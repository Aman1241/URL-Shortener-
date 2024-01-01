# URL-Shortener-
import pyshorteners
long_url = input("Enter the URL to be shorten: ")

type_tiny = pyshorteners.Shortener()
short_url = type_tiny.tinyurl.short(long_url)

print(f"The shortened URL: {short_url}")

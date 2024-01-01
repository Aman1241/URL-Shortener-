# URL-Shortener-
import secrets
import string

def generate_password(length=10):
    characters = string.ascii_letters + string.digits + string.punctuation
    password = ''.join(secrets.choice(characters) for i in range(length))
    return password

random_password = generate_password()
print(f"Random password: {random_password}")

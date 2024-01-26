- 👋 Hi, I’m @RamyRayrdragon
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
RamyRayrdragon/RamyRayrdragon is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
def main():
    print('Welcome to Lebanese Are Great!')
    print('We are excited to share our business with you.')
    print('Our business is dedicated to providing quality Lebanese products and services.')
    print('Join us to explore the rich flavors and traditions of Lebanon.')

    registration = input('Would you like to register for more information? (yes/no): ').strip().lower()
    if registration == 'yes':
        print('Thank you for your interest! Please provide your details.')
        name = input('Name: ')
        email = input('Email: ')
        print(f'Thank you, {name}, for registering. We will send updates to {email} soon!')
    else:
        print('No problem! Feel free to visit our website anytime for more information.')

if __name__ == '__main__':
    main()

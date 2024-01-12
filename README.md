# Random IT Fact Generator

import random

def get_random_it_fact():
    it_facts = [
        "The first computer programmer was a woman named Ada Lovelace.",
        "The term 'bug' in computer science originated from a moth found in a relay of the Harvard Mark II computer in 1947.",
        "The world's first website was created by Tim Berners-Lee and went live on August 6, 1991.",
        "The average computer user blinks 7 times a minute, while the normal rate is 20 blinks per minute.",
        "The QWERTY keyboard layout was designed to slow down typing and prevent jamming of mechanical keys on early typewriters.",
    ]
    return random.choice(it_facts)

def main():
    it_fact = get_random_it_fact()
    print("Random IT Fact:")
    print(it_fact)

if __name__ == "__main__":
    main()

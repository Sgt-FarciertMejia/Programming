#Input a string return int
def string_to_number(s):
    # ... your code here
    try:
        return int(s)
    except (ValueError):
        return "Input is not valid " 

#String cutter prints everything but first and last letter
def remove_char(s):
    return s[1 : -1]

# BEGIN (write your solution here)
def is_degenerated(line):
    if line[0] == line[1]:
        return True


def is_vertical(line):
    if line[0][0] == line[1][0] and line[0][1] != line[1][1]:
        return True


def is_horizontal(line):
    if line[0][1] == line[1][1] and line[0][0] != line[1][0]:
        return True


def is_inclined(line):
    if not (is_degenerated(line) or is_vertical(line) or is_horizontal(line)):
        return True
# END

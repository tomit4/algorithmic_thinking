CC=gcc
CFLAGS=-Wall -Wextra -Werror -Wpedantic -std=c99
INPUT_FILE=./food_lines.c
OUTPUT_FILE=../bin/intro/food_lines

food_lines:
	$(CC) $(CFLAGS) -o  $(OUTPUT_FILE) $(INPUT_FILE)

execute:
	../bin/intro/food_lines < ./food.txt

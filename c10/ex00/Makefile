# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: cacharle <charles.cabergs@gmail.com>       +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2019/07/17 08:40:22 by cacharle          #+#    #+#              #
#    Updated: 2019/07/17 08:45:51 by cacharle         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

OUT = ft_display_file
CC = gcc
CCFLAGS = -Wall -Wextra -Werror

.PHONY: all
all: $(OUT)
	$(CC) $(CCFLAGS) -o $(OUT) main.o


$(OUT): main.o
	$(CC) $(CCFLAGS) -o $(OUT) main.o

main.o: main.c
	$(CC) $(CCFLAGS) -c main.c -o main.o

.PHONY: clean
clean:
	rm -f main.o

.PHONY: clean
fclean: clean
	rm -f $(OUT)

.PHONY: re
re: fclean all

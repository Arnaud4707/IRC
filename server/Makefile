
SRCS =	main.cpp

OBJS = ${SRCS:.cpp=.o}

NAME = ircserv

CFLAGS = -I. -g3 -Wall -Werror -Wextra -std=c++98

CC = c++
RM = rm -f

${NAME}:	${OBJS}
	${CC} ${CFLAGS} -o ${NAME} ${OBJS}

all:		${NAME}

clean:
	${RM} ${OBJS} *~ #*#

fclean:		clean
	${RM} ${NAME}

re:		fclean all

WEBVTT

1
00:00:00.112 --> 00:00:08.433
[MUSIC]

2
00:00:08.433 --> 00:00:11.370
Hi, and
welcome to lecture two of module two.

3
00:00:13.050 --> 00:00:16.340
In this lecture, we'll talk about
the Flow of Control structures in Ruby.

4
00:00:16.340 --> 00:00:18.820
The if, the else, the case.

5
00:00:18.820 --> 00:00:25.210
Ruby also adds two new ones, until and
unless, we'll talk about those.

6
00:00:25.210 --> 00:00:26.600
There's also the while and for.

7
00:00:26.600 --> 00:00:32.550
We'll talk about what is true and
what is false when comparing things.

8
00:00:33.730 --> 00:00:36.100
And, what in the world
is this === operator?

9
00:00:38.240 --> 00:00:42.850
So, the if, the elsif are probably
structures with which

10
00:00:42.850 --> 00:00:45.340
a lot of us are familiar from
other programming languages.

11
00:00:46.510 --> 00:00:51.260
The difference is that in Ruby there's no
parentheses or curly braces when you find

12
00:00:51.260 --> 00:00:56.390
those, and you use end to
close the flow control block.

13
00:00:56.390 --> 00:00:59.849
So whether it's just if statement,
or if and else statement,

14
00:00:59.849 --> 00:01:02.476
you're always going to
have the end at the end.

15
00:01:04.076 --> 00:01:09.450
So in this case you have the a variable
which gets assigned a value of five.

16
00:01:09.450 --> 00:01:12.055
So when you assign it,
it's a single equals.

17
00:01:12.055 --> 00:01:14.905
When you're comparing,
it's a double equals and

18
00:01:14.905 --> 00:01:18.775
in this case five matches the second
condition, so you print out a five.

19
00:01:20.275 --> 00:01:24.645
Now Ruby also adds this
interesting keyword unless, and

20
00:01:24.645 --> 00:01:31.080
unless is basically if something
is not equal to something else.

21
00:01:31.080 --> 00:01:34.550
So, in this case,
a is five, unless a is six.

22
00:01:34.550 --> 00:01:37.680
Do what you got to do, so
that's what's printed out.

23
00:01:37.680 --> 00:01:38.420
A is not six.

24
00:01:40.520 --> 00:01:42.530
Then there is your while loop, so

25
00:01:42.530 --> 00:01:47.670
you have a variable,
which gets assigned a value of ten.

26
00:01:47.670 --> 00:01:53.110
And while a is greater than nine, you keep
on executing the contents of the loop.

27
00:01:54.680 --> 00:02:00.270
In this case, you're subtracting one from
a, every time going through the loop,

28
00:02:00.270 --> 00:02:04.470
so this will only execute
once because the second time,

29
00:02:04.470 --> 00:02:07.480
a is going to be not greater than nine.

30
00:02:07.480 --> 00:02:09.894
So therefore the only output
from this loop is gonna be 10.

31
00:02:11.630 --> 00:02:19.400
Then you have a Ruby specific one which
is the opposite of while, it's until.

32
00:02:19.400 --> 00:02:20.490
So a is nine.

33
00:02:20.490 --> 00:02:27.280
Until a is greater than or equal to
ten keep on printing a value of nines,

34
00:02:27.280 --> 00:02:31.991
so this will also only execute
once because the second

35
00:02:31.991 --> 00:02:37.550
time through the loop it's gonna be ten so
it will not execute.

36
00:02:37.550 --> 00:02:44.280
Now Ruby gets even more expressive
in that there's this modifier form,

37
00:02:44.280 --> 00:02:48.270
so the modifier form lets you
print things out in one line.

38
00:02:48.270 --> 00:02:51.890
So puts one liner if A is five and

39
00:02:51.890 --> 00:02:56.720
B is zero, so
it almost reads like very natural English.

40
00:02:56.720 --> 00:02:58.640
And this applies to while as well.

41
00:02:58.640 --> 00:03:03.990
So you have a variable called times two
which initially gets assigned to two,

42
00:03:03.990 --> 00:03:10.138
and you keep on multiplying this variable

43
00:03:10.138 --> 00:03:17.760
by two as long as this variable
times two is less than a hundred.

44
00:03:17.760 --> 00:03:20.688
So can you guess what
the answer to this one is?

45
00:03:23.397 --> 00:03:26.406
If you guessed 128, you are correct.

46
00:03:28.197 --> 00:03:30.800
Now, the next thing we'll talk
about is the true and false.

47
00:03:30.800 --> 00:03:32.480
What is true and what is false in Ruby?

48
00:03:34.160 --> 00:03:38.220
As it turns out, the only things which
are false are gonna be your false

49
00:03:39.280 --> 00:03:44.480
literal or false object and nil object.

50
00:03:44.480 --> 00:03:48.360
Everything else is true, so
if you're used to from other languages for

51
00:03:48.360 --> 00:03:52.210
example that zero is false,
that's not true in Ruby.

52
00:03:52.210 --> 00:03:54.130
In Ruby, zero is true.

53
00:03:54.130 --> 00:03:58.380
Or a false literal string is false?

54
00:03:58.380 --> 00:03:59.320
No it's not, it's true.

55
00:04:00.640 --> 00:04:05.576
Or an empty string maybe you're used
to from some other languages that

56
00:04:05.576 --> 00:04:08.270
empty string is a false value.

57
00:04:08.270 --> 00:04:09.460
That's not true either.

58
00:04:10.470 --> 00:04:15.910
So the only things which are false in Ruby

59
00:04:15.910 --> 00:04:22.160
are going to be a false literal or
a nil object.

60
00:04:22.160 --> 00:04:25.040
Everything else is going to be true.

61
00:04:25.040 --> 00:04:29.160
Now if you're using a string literal,
for example, nil or

62
00:04:29.160 --> 00:04:34.140
false or really any other string literal
in your if statement, you are going to get

63
00:04:34.140 --> 00:04:39.340
a warning from an interpreter that
says string literal in condition.

64
00:04:39.340 --> 00:04:44.590
Because you're not saying
if false equals false or

65
00:04:44.590 --> 00:04:48.760
doing any other comparisons, so if
the interpreter says to you really did you

66
00:04:48.760 --> 00:04:54.550
really mean to just say a string as
your condition of your if statement.

67
00:04:54.550 --> 00:04:57.290
That's always gonna be true so
why would do that?

68
00:04:57.290 --> 00:05:00.000
So it's almost like it's clueing
you in that there's an issue.

69
00:05:02.490 --> 00:05:03.370
Triple equals.

70
00:05:04.640 --> 00:05:08.520
So you're gonna see this in some cases.

71
00:05:08.520 --> 00:05:12.570
So most of the time,
you should be using a double equals and

72
00:05:12.570 --> 00:05:18.130
that's what most Ruby objects use,
double equals.

73
00:05:18.130 --> 00:05:23.110
But sometimes there is this interesting
implementation of a triple equals, and

74
00:05:23.110 --> 00:05:26.500
triple equals basically is
a special kind of equals.

75
00:05:26.500 --> 00:05:31.410
So for example,
to jump straight into examples, you

76
00:05:31.410 --> 00:05:36.440
have a regular expression, and
regular expressions are outside

77
00:05:36.440 --> 00:05:40.840
the scope of this course but they're
pretty cool so you should check them out.

78
00:05:40.840 --> 00:05:47.320
You have a regular expression,
sera, which is === to coursera.

79
00:05:47.320 --> 00:05:49.030
Is it really equal?

80
00:05:49.030 --> 00:05:49.870
No, of course not.

81
00:05:49.870 --> 00:05:54.360
One is a string and one is a regular
expression, they're not really equal.

82
00:05:54.360 --> 00:05:56.470
We're not even asking if they're equal.

83
00:05:56.470 --> 00:06:01.840
But, it would be cool to say, does this
regular expression match a string literal,

84
00:06:01.840 --> 00:06:03.506
and that's what this triple equal does.

85
00:06:03.506 --> 00:06:09.600
Now, as you could see here,

86
00:06:09.600 --> 00:06:15.310
a triple equals will also work if you're
just comparing a string to itself.

87
00:06:15.310 --> 00:06:20.910
That's also fine because triple equals
most of the time just delegates

88
00:06:20.910 --> 00:06:25.860
to a double equals, so it's almost
like a super set of a double equals.

89
00:06:27.090 --> 00:06:30.860
Another example is integer
class equal to 21.

90
00:06:30.860 --> 00:06:35.550
Well no, one is integer class and
one is a value 21.

91
00:06:35.550 --> 00:06:41.170
But it would be pretty cool to
know if this value, whatever

92
00:06:41.170 --> 00:06:46.410
value you're looking at is an integer,
and the triple equal lets you do that.

93
00:06:47.550 --> 00:06:50.090
Next, we'll talk about case expressions,
and

94
00:06:50.090 --> 00:06:54.640
the case expressions
have two flavors in Ruby.

95
00:06:54.640 --> 00:07:00.890
One flavor is very similar to your series
of if statements, if else statements.

96
00:07:00.890 --> 00:07:06.370
So it's very similar to the if else
that we already saw in previous slides.

97
00:07:06.370 --> 00:07:11.550
And this is just sort of a different
keyword, it's case instead of if else.

98
00:07:11.550 --> 00:07:13.420
So, that's the first flavor.

99
00:07:13.420 --> 00:07:19.020
The second flavor is more interesting
in that you actually specify the target

100
00:07:19.020 --> 00:07:24.150
next to the case key word, and then

101
00:07:24.150 --> 00:07:29.250
what happens is that each clause inside
the when gets compared to that target.

102
00:07:29.250 --> 00:07:31.020
And we see an example of
that in the next slide.

103
00:07:32.360 --> 00:07:35.900
And that's actually where the triple
equals, which we just covered in

104
00:07:35.900 --> 00:07:40.140
the previous slide, comes in, it's also
called the case equality operator.

105
00:07:40.140 --> 00:07:44.490
So, when things are being compared for

106
00:07:44.490 --> 00:07:49.210
an each when clause, it's actually using
the triple equals operator for that.

107
00:07:50.450 --> 00:07:55.770
Now, just one last note on the case
expressions is that if you're

108
00:07:55.770 --> 00:08:00.360
used to the C style,
the C family of languages where

109
00:08:00.360 --> 00:08:05.200
you have a fall-through logic inside your
case statements, that's not the case.

110
00:08:05.200 --> 00:08:10.440
Ruby, one case, the only case that
actually matches gets executed and

111
00:08:10.440 --> 00:08:11.110
no other cases.

112
00:08:12.820 --> 00:08:17.170
So to show you an example of
the two flavors we just discussed,

113
00:08:17.170 --> 00:08:18.830
the first flavor is very simple.

114
00:08:18.830 --> 00:08:23.400
You have, for example a variable,
but then the actual

115
00:08:23.400 --> 00:08:28.140
comparisons inside the case have
nothing to do with that variable.

116
00:08:28.140 --> 00:08:31.560
I mean you can compare that variable, you
could compare other statements, you could

117
00:08:31.560 --> 00:08:35.670
have a default statement, really has
nothing to do with the actual variable.

118
00:08:35.670 --> 00:08:36.830
It's almost like an if else.

119
00:08:36.830 --> 00:08:38.300
That's the first flavor.

120
00:08:38.300 --> 00:08:45.050
The second flavor, you have the actual
target right next to the case

121
00:08:45.050 --> 00:08:49.395
so every condition in the case

122
00:08:49.395 --> 00:08:54.870
implicitly compares
itself to actual targets.

123
00:08:54.870 --> 00:08:56.660
In this case, you have

124
00:08:57.920 --> 00:09:03.160
regular expression doing the triple
equals, that's what case uses,

125
00:09:03.160 --> 00:09:08.980
uses the triple equals operator to
compare itself to a name target.

126
00:09:11.880 --> 00:09:15.710
For loop I did say we're going
to talk about it, but I lied.

127
00:09:17.140 --> 00:09:25.050
For loop is hardly used in Ruby and
preference is given to each and times.

128
00:09:25.050 --> 00:09:27.530
So the times we already
saw all the way back

129
00:09:29.060 --> 00:09:34.040
in beginning of the last lecture,
and we also going to see each, and

130
00:09:34.040 --> 00:09:39.210
I'll talk about both of these when we
talk about blocks, which is coming up.

131
00:09:40.980 --> 00:09:46.290
Now if you do want to see an example
of a for loop, Ruby does have one.

132
00:09:46.290 --> 00:09:51.820
So you have a for some integer in a range,

133
00:09:51.820 --> 00:09:55.880
a range again is a data type
which we haven't talked about, so

134
00:09:55.880 --> 00:10:00.880
you could say for
i in this range of 0 to 2,

135
00:10:00.880 --> 00:10:05.250
print out the variable i and
you have 0, 1, and 2.

136
00:10:05.250 --> 00:10:08.440
So this is your typical for
loop, but like I said, for

137
00:10:08.440 --> 00:10:12.090
loops exist in Ruby, but
they are not used much.

138
00:10:13.980 --> 00:10:17.170
So in summary, there are lots
of options for flow of control.

139
00:10:17.170 --> 00:10:24.030
You have if, else, the cases,
the while loops, the until, the unless.

140
00:10:24.030 --> 00:10:26.120
And then you also have the modifier form,

141
00:10:26.120 --> 00:10:29.620
which is a very interesting way
to be very expressive in Ruby.

142
00:10:29.620 --> 00:10:33.829
And what you should remember
is that non-nil and

143
00:10:33.829 --> 00:10:37.740
non-false values are always gonna be true.

144
00:10:37.740 --> 00:10:44.180
And the only things which are gonna be
false are your false and your nil object.

145
00:10:44.180 --> 00:10:45.270
So what's next?

146
00:10:45.270 --> 00:10:48.155
Next we're gonna talk about
the functions and the methods in Ruby.
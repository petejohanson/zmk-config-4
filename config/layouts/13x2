/* This file is copied and then modified from https://github.com/urob/zmk-nodefree-config/blob/973f717c6bbde9cf452a4da88ac9a7f80cdd4bef/keypos_def/keypos_34keys.h
 * LICENSE for that repo is inlined below.

 * MIT License
 *
 * Copyright (c) 2023 Robert U
 * 
 * Permission is hereby granted, free of charge, to any person obtaining a copy
 * of this software and associated documentation files (the "Software"), to deal
 * in the Software without restriction, including without limitation the rights
 * to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 * copies of the Software, and to permit persons to whom the Software is
 * furnished to do so, subject to the following conditions:
 * 
 * The above copyright notice and this permission notice shall be included in all
 * copies or substantial portions of the Software.
 * 
 * THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
 * IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
 * FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 * AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 * LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 * OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 * SOFTWARE.
 */

/*                             19x2 KEY MATRIX / LAYOUT MAPPING

  ╭────────────────────────────────┬───────────────────────────────╮ 
  │  1   2   3   4   5             │           6   7   8   9   10  │
  │ 11  12  13  14  15             │          16  17  18  19   20  │
  │ 21  22  23  24  25             │          26  27  28  29   30  │
  ╰───────────────╮ 31  32  33  34 │ 22 23 24 25  ╭────────────────╯
                  ╰────────────────┴──────────────╯
  ╭────────────────────────────────┬───────────────────────────────╮
  │ LT0 LT1 LT2 LT3 LT4            │          RT0 RT1 RT2 RT3 RT4  │
  │ LM0 LM1 LM2 LM3 LM4            │          RM0 RM1 RM2 RM3 RM4  │
  │ LB0 LB1 LB2 LB3 LB4            │          RB0 RB1 RB2 RB3 RB4  │
  ╰───────────────╮ LH0 LH1 LH2 LH3│RH0 RH1 RH2 RH3 ╭──────────────╯ 
                  ╰────────────────┴────────────────╯
*/

#pragma once

#define LT0  1  // left-top row
#define LT1  2
#define LT2  3
#define LT3  4
#define LT4  5

#define RT0  6  // right-top row
#define RT1  7
#define RT2  8
#define RT3  9
#define RT4  10

#define LM0 11  // left-middle row
#define LM1 12
#define LM2 13
#define LM3 14
#define LM4 15

#define RM0 16  // right-middle row
#define RM1 17
#define RM2 18
#define RM3 19
#define RM4 20

#define LB0 21  // left-bottom row
#define LB1 22
#define LB2 23
#define LB3 24
#define LB4 25

#define RB1 23  // right-bottom row
#define RB2 24
#define RB3 25

#define LH0 26  // left thumb key

#define RH0 27  // right thumb key

#define KEYS_L LT0 LT1 LT2 LT3 LT4 LM0 LM1 LM2 LM3 LM4     LB1 LB2 LB3      // left-hand keys
#define KEYS_R RT0 RT1 RT2 RT3 RT4 RM0 RM1 RM2 RM3 RM4     RB1 RB2 RB3      // right-hand keys
#define THUMBS         LH0 RH0                                              // thumb keys

#define LAYER_FROM36( \
    k00, k01, k02, k03, k04, k05, k06, k07, k08, k09, \
    k10, k11, k12, k13, k14, k15, k16, k17, k18, k19, \
    k20, k21, k22, k23, k24, k25, k26, k27, k28, k29, \
              k30, k31, k32, k33, k34, k35            \
) \
    k00  k01  k02  k03  k04  k05  k06  k07  k08  k09  \
    k10  k11  k12  k13  k14  k15  k16  k17  k18  k19  \
         k21  k22  k23            k26  k27  k28       \
                        k32  k33

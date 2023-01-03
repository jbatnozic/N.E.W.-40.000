# TN Tables Analysis

This page describes the concepts and ideas behind TN (Target Number) tables in N.E.W. 40,000, how they work and what
problems they address.

## Normal

The normal, most commonly used TN table is as follows (`Exp` = Exponent, `--` = Double impairment, `-` = Impairment,
`N` = Normal, `+` = Advantage, `++` = Double advantage):

 Exp | -- |  - |  N |  + | ++ |
-----|----|----|----|----|----|
  1  | 64 | 62 | 61 | 55 | 54 |
  2  | 62 | 56 | 54 | 51 | 45 |
  3  | 61 | 54 | 51 | 44 | 41 |
  4  | 55 | 52 | 44 | 36 | 32 |
  5  | 54 | 45 | 41 | 32 | 24 |
  6  | 52 | 43 | 34 | 25 | 15 |
  7  | 51 | 41 | 31 | 21 | 12 |
  8  | 46 | 35 | 24 | 13 | 12 |
  9  | 44 | 33 | 21 | 12 | 12 |

**Description:** In the central (normal) column, the odd-numbered Exponents 1, 3, 5, 7 and 9 correspond to 6+, 5+, 4+,
3+ and 2+ dice rolls, respectively. Thus a Ballistic Skill of 5, for example, in N.E.W. 40,000 is equivalent to a
Ballistic Skill of 4+ in regular Warhammer 40,000 (9th edition). The even numbered Exponents 2, 4, 6 and 8 sit exactly
between as far as chances of success go. In fact, you'll notice that all steps between Exponent 1 and Exponent 9 are in
8.33% increments. As for Advantages and Impairments: the idea is that with 1 Advantage, the chances of success go up
25%, and with 2+ Advantages, the chances of success go up 50% (equating to a 25% and 50% damage increase, respectively,
over a sufficient amount of rolls). With Impairments the story is reversed, with chances of success going down by 25%
(1 Impairment) and 50% (2+ impairments). However, due to the limited resolution of dice, these are sometimes small
deviations from the ideal success rates, usually +/-5%. The deviations are a bit bigger at the extremes of the spectrum,
with very low or very high Exponents.

**Additional Note:** In regular Warhammer 40,000 (9th edition) the value of a +1 or -1 modifier to your rolls varies
wildly. A +/-1 modifier for a 5+ Ballistic Skill (+50% increase / -50% reduction) is much more impactful than for a 2+
Ballistic Skill (+0% increase \[capped to 2+] / -20% reduction). In N.E.W. 40,000 a value of an Advantage or Impairment
is very consistent across the board.

The chances of success with these TNs are listed below.

The notation is as such: `chance of success (chance insrease or decrease relative to central [normal] column)`

 Exp |        --        |         -         |         N         |         +         |        ++         |
-----|------------------|-------------------|-------------------|-------------------|-------------------|
  1  |  8.33% (-50.00%) |  13.89% (-16.67%) |  16.67% ( +0.00%) |  22.22% (+33.33%) |  25.00% (+50.00%) | 
  2  | 13.89% (-44.44%) |  19.44% (-22.22%) |  25.00% ( +0.00%) |  33.33% (+33.33%) |  38.89% (+55.56%) | 
  3  | 16.67% (-50.00%) |  25.00% (-25.00%) |  33.33% ( +0.00%) |  41.67% (+25.00%) |  50.00% (+50.00%) | 
  4  | 22.22% (-46.67%) |  30.56% (-26.67%) |  41.67% ( +0.00%) |  52.78% (+26.67%) |  63.89% (+53.33%) | 
  5  | 25.00% (-50.00%) |  38.89% (-22.22%) |  50.00% ( +0.00%) |  63.89% (+27.78%) |  75.00% (+50.00%) | 
  6  | 30.56% (-47.62%) |  44.44% (-23.81%) |  58.33% ( +0.00%) |  72.22% (+23.81%) |  88.89% (+52.38%) | 
  7  | 33.33% (-50.00%) |  50.00% (-25.00%) |  66.67% ( +0.00%) |  83.33% (+25.00%) |  97.22% (+45.83%) | 
  8  | 36.11% (-51.85%) |  55.56% (-25.93%) |  75.00% ( +0.00%) |  94.44% (+25.93%) |  97.22% (+29.63%) | 
  9  | 41.67% (-50.00%) |  61.11% (-26.67%) |  83.33% ( +0.00%) |  97.22% (+16.67%) |  97.22% (+16.67%) |

## Overwatch

The Overwatch TN table is as follows (`Exp` = Exponent, `--` = Double impairment, `-` = Impairment,
`N` = Normal, `+` = Advantage, `++` = Double advantage):

 Exp | -- |  - |  N |  + | ++ |
-----|----|----|----|----|----|
  1  | 66 | 65 | 64 | 63 | 62 |
  2  | 64 | 63 | 62 | 61 | 56 |
  3  | 64 | 62 | 61 | 55 | 54 |
  4  | 63 | 61 | 55 | 53 | 51 |
  5  | 62 | 56 | 54 | 52 | 45 |
  6  | 61 | 55 | 52 | 46 | 43 |
  7  | 61 | 54 | 51 | 44 | 41 |
  8  | 56 | 53 | 45 | 41 | 34 |
  9  | 55 | 52 | 44 | 36 | 32 |

**Description:** The idea of the Overwatch table is simple: It should mimic the regular TN table, but with the
success rate cut in half. For example, a model that hits 66% of the time using the regulat TN table will hit 33% when
using the Overwatch table. 

**Additional Note:** In regular Warhammer 40,000 (9th edition), firing Overwatch limits you to hitting on sixes. For a
model that usually hits on a 5+, this results in a 50% damage reduction (half as much damage done), while for a model
that usually hits on 2+, this results in 80% damage reduction (1/5th as much damage done). In N.E.W. 40,000, the
reduction is quite consistent at around 50%.

The chances of success with these TNs are listed below.

The notation is as such: `chance of success (chance insrease or decrease relative to central [normal] column)`

 Exp |        --        |         -         |         N         |         +         |        ++         |
-----|------------------|-------------------|-------------------|-------------------|-------------------|
  1  |  2.78% (-66.67%) |   5.56% (-33.33%) |   8.33% ( +0.00%) |  11.11% (+33.33%) |  13.89% (+66.67%) |   
  2  |  5.56% (-60.00%) |  11.11% (-20.00%) |  13.89% ( +0.00%) |  16.67% (+20.00%) |  19.44% (+40.00%) |   
  3  |  8.33% (-50.00%) |  13.89% (-16.67%) |  16.67% ( +0.00%) |  22.22% (+33.33%) |  25.00% (+50.00%) |   
  4  | 11.11% (-50.00%) |  16.67% (-25.00%) |  22.22% ( +0.00%) |  27.78% (+25.00%) |  33.33% (+50.00%) |   
  5  | 13.89% (-44.44%) |  19.44% (-22.22%) |  25.00% ( +0.00%) |  30.56% (+22.22%) |  38.89% (+55.56%) |   
  6  | 16.67% (-45.45%) |  22.22% (-27.27%) |  30.56% ( +0.00%) |  36.11% (+18.18%) |  44.44% (+45.45%) |   
  7  | 16.67% (-50.00%) |  25.00% (-25.00%) |  33.33% ( +0.00%) |  41.67% (+25.00%) |  50.00% (+50.00%) |   
  8  | 19.44% (-50.00%) |  27.78% (-28.57%) |  38.89% ( +0.00%) |  50.00% (+28.57%) |  58.33% (+50.00%) |   
  9  | 22.22% (-46.67%) |  30.56% (-26.67%) |  41.67% ( +0.00%) |  52.78% (+26.67%) |  63.89% (+53.33%) |

## Relative

The table below shows the chance of succeeding a roll with the Overwatch table compared to the normal table. Ideally
it would show exactly 50% everywhere, but that isn't quite possible due to dice limitations (it's very close though).

 Exp |   --   |    -    |    N    |    +    |    ++   |
-----|--------|---------|---------|---------|---------|
  1  | 33.33% |  40.00% |  50.00% |  50.00% |  55.56% |  
  2  | 40.00% |  57.14% |  55.56% |  50.00% |  50.00% |  
  3  | 50.00% |  55.56% |  50.00% |  53.33% |  50.00% |  
  4  | 50.00% |  54.55% |  53.33% |  52.63% |  52.17% |  
  5  | 55.56% |  50.00% |  50.00% |  47.83% |  51.85% |  
  6  | 54.55% |  50.00% |  52.38% |  50.00% |  50.00% |  
  7  | 50.00% |  50.00% |  50.00% |  50.00% |  51.43% |  
  8  | 53.85% |  50.00% |  51.85% |  52.94% |  60.00% |  
  9  | 53.33% |  50.00% |  50.00% |  54.29% |  65.71% |

## OLD Normal Table

The old and terrible (for many reasons) TN table from the first version of N.E.W. 40,000. Feel free to facepalm.

 Exp | -- |  - |  N |  + | ++ |
-----|----|----|----|----|----|
  1  | 65 | 63 | 61 | 53 | 45 |
  2  | 63 | 61 | 54 | 46 | 42 |
  3  | 61 | 54 | 51 | 43 | 35 |
  4  | 55 | 52 | 44 | 36 | 32 |
  5  | 53 | 45 | 41 | 33 | 25 |
  6  | 51 | 42 | 34 | 26 | 23 |
  7  | 45 | 36 | 31 | 24 | 21 |
  8  | 43 | 33 | 24 | 21 | 15 |
  9  | 41 | 31 | 21 | 15 | 13 |

Probabilities:

 Exp |        --        |         -         |         N         |         +         |        ++          |
-----|------------------|-------------------|-------------------|-------------------|--------------------|
  1  |  5.56% (-66.67%) |  11.11% (-33.33%) |  16.67% ( +0.00%) |  27.78% (+66.67%) |  38.89% (+133.33%) |    
  2  | 11.11% (-55.56%) |  16.67% (-33.33%) |  25.00% ( +0.00%) |  36.11% (+44.44%) |  47.22% (+88.89%)  |    
  3  | 16.67% (-50.00%) |  25.00% (-25.00%) |  33.33% ( +0.00%) |  44.44% (+33.33%) |  55.56% (+66.67%)  |    
  4  | 22.22% (-46.67%) |  30.56% (-26.67%) |  41.67% ( +0.00%) |  52.78% (+26.67%) |  63.89% (+53.33%)  |    
  5  | 27.78% (-44.44%) |  38.89% (-22.22%) |  50.00% ( +0.00%) |  61.11% (+22.22%) |  72.22% (+44.44%)  |    
  6  | 33.33% (-42.86%) |  47.22% (-19.05%) |  58.33% ( +0.00%) |  69.44% (+19.05%) |  77.78% (+33.33%)  |    
  7  | 38.89% (-41.67%) |  52.78% (-20.83%) |  66.67% ( +0.00%) |  75.00% (+12.50%) |  83.33% (+25.00%)  |    
  8  | 44.44% (-40.74%) |  61.11% (-18.52%) |  75.00% ( +0.00%) |  83.33% (+11.11%) |  88.89% (+18.52%)  |    
  9  | 50.00% (-40.00%) |  66.67% (-20.00%) |  83.33% ( +0.00%) |  88.89% ( +6.67%) |  94.44% (+13.33%)  | 

## OLD Overwatch table

Equally terrible Overwatch table from the original version of N.E.W. 40,000.

 Exp | -- |  - |  N |  + | ++ |
-----|----|----|----|----|----|
  1  | 66 | 65 | 64 | 62 | 56 |
  2  | 65 | 64 | 63 | 61 | 55 |
  3  | 64 | 63 | 61 | 55 | 53 |
  4  | 63 | 61 | 56 | 54 | 52 |
  5  | 62 | 56 | 54 | 52 | 51 |
  6  | 61 | 55 | 53 | 51 | 46 |
  7  | 56 | 53 | 51 | 45 | 44 |
  8  | 55 | 52 | 46 | 44 | 43 |
  9  | 54 | 51 | 44 | 43 | 42 |

Probabilities:

 Exp |        --        |         -         |         N         |         +         |        ++          |
-----|------------------|-------------------|-------------------|-------------------|--------------------|
  1  |  2.78% (-66.67%) |   5.56% (-33.33%) |   8.33% ( +0.00%) |  13.89% (+66.67%) |  19.44% (+133.33%) |    
  2  |  5.56% (-50.00%) |   8.33% (-25.00%) |  11.11% ( +0.00%) |  16.67% (+50.00%) |  22.22% (+100.00%) |    
  3  |  8.33% (-50.00%) |  11.11% (-33.33%) |  16.67% ( +0.00%) |  22.22% (+33.33%) |  27.78% (+66.67%)  |    
  4  | 11.11% (-42.86%) |  16.67% (-14.29%) |  19.44% ( +0.00%) |  25.00% (+28.57%) |  30.56% (+57.14%)  |    
  5  | 13.89% (-44.44%) |  19.44% (-22.22%) |  25.00% ( +0.00%) |  30.56% (+22.22%) |  33.33% (+33.33%)  |    
  6  | 16.67% (-40.00%) |  22.22% (-20.00%) |  27.78% ( +0.00%) |  33.33% (+20.00%) |  36.11% (+30.00%)  |    
  7  | 19.44% (-41.67%) |  27.78% (-16.67%) |  33.33% ( +0.00%) |  38.89% (+16.67%) |  41.67% (+25.00%)  |    
  8  | 22.22% (-38.46%) |  30.56% (-15.38%) |  36.11% ( +0.00%) |  41.67% (+15.38%) |  44.44% (+23.08%)  |    
  9  | 25.00% (-40.00%) |  33.33% (-20.00%) |  41.67% ( +0.00%) |  44.44% ( +6.67%) |  47.22% (+13.33%)  | 

## Propragm to calculate (C++)

Below is a C++ program used to calculate and display the probabilities shown in this document. Not my proudest piece of
code.

```cpp
#include <cmath>
#include <iostream>
#include <stdexcept>

/// Classic
// const int kNormalTargetNumbers[9][5] = {
//     {65, 63, 61, 53, 45},
//     {63, 61, 54, 46, 42},
//     {61, 54, 51, 43, 35},
//     {55, 52, 44, 36, 32},
//     {53, 45, 41, 33, 25},
//     {51, 42, 34, 26, 23},
//     {45, 36, 31, 24, 21},
//     {43, 33, 24, 21, 15},
//     {41, 31, 21, 15, 13}
// };

/// Classic
// const int kOverwatchTargetNumbers[9][5] = {
//     {66, 65, 64, 62, 56},
//     {65, 64, 63, 61, 55},
//     {64, 63, 61, 55, 53},
//     {63, 61, 56, 54, 52},
//     {62, 56, 54, 52, 51},
//     {61, 55, 53, 51, 46},
//     {56, 53, 51, 45, 44},
//     {55, 52, 46, 44, 43},
//     {54, 51, 44, 43, 42}
// };

/// New
const int kNormalTargetNumbers[9][5] = {
    {64, 62, 61, 55, 54},
    {62, 56, 54, 51, 45},
    {61, 54, 51, 44, 41},
    {55, 52, 44, 36, 32},
    {54, 45, 41, 32, 24},
    {52, 43, 34, 25, 15},
    {51, 41, 31, 21, 12},
    {46, 35, 24, 13, 12},
    {44, 33, 21, 12, 12}
};

/// New
const int kOverwatchTargetNumbers[9][5] = {
    {66, 65, 64, 63, 62},
    {65, 63, 62, 61, 56},
    {64, 62, 61, 55, 54},
    {63, 61, 55, 53, 51},
    {62, 56, 54, 52, 45},
    {61, 55, 52, 46, 43},
    {61, 54, 51, 44, 41},
    {56, 53, 45, 41, 34},
    {55, 52, 44, 36, 32},
};

#define EXP1 0
#define EXP9 8
#define DOUBLE_DISADV 0
#define DISADV 1
#define NORMAL 2
#define ADVANTAGE 3
#define DOUBLE_ADVANTAGE 4

double GetChanceOfMeetingTN(int tn) {
    const int kPossibleResults[36] = {
        11, 12, 13, 14, 15, 16,
        21, 22, 23, 24, 25, 26,
        31, 32, 33, 34, 35, 36,
        41, 42, 43, 44, 45, 46,
        51, 52, 53, 54, 55, 56,
        61, 62, 63, 64, 65, 66
    };
    
    for (int i = 0; i < 36; i += 1) {
        if (kPossibleResults[i] >= tn) {
            return (static_cast<double>(36 - i) / 36.0);
        }
    }
    
    throw std::runtime_error("GetChanceOfMeetingTN fail");
}

int GetOptimalOverwatchTNForNormalTN(int normalTN) {
    // std::printf("Finding best OW TN for TN %d\n", normalTN);
    
    const int kPossibleTNs[36] = {
        11, 12, 13, 14, 15, 16,
        21, 22, 23, 24, 25, 26,
        31, 32, 33, 34, 35, 36,
        41, 42, 43, 44, 45, 46,
        51, 52, 53, 54, 55, 56,
        61, 62, 63, 64, 65, 66
    };
    
    const double targetChance = 0.5 * GetChanceOfMeetingTN(normalTN);
    
    struct {
        int tn = 0;
        double chanceOffset = -1000000.0;
    } currentBest;
    
    for (int tn : kPossibleTNs) {
        const double chance = GetChanceOfMeetingTN(tn);
        const double chanceOffset = chance - targetChance;
        
        if (std::abs(chanceOffset) <= std::abs(currentBest.chanceOffset)) {
            if (std::abs(
                    std::abs(chanceOffset) - std::abs(currentBest.chanceOffset)
                ) < 0.0005) 
            {
                // Basically equivalent just opposite signs:
                // pick bigger overall chance of success
                if (chance > targetChance + currentBest.chanceOffset) {
                    // std::printf("!(%d, %+5.2f) better than (%d, %+5.2f) for TN (%d, %+5.2f)\n",
                    //             tn, chanceOffset, currentBest.tn, currentBest.chanceOffset, normalTN, targetChance);
                                
                    // Swap
                    currentBest.tn = tn;
                    currentBest.chanceOffset = chanceOffset;
                } else {
                    // std::printf("!(%d, %+5.2f) not considered further\n",
                    //             tn, chanceOffset);
                }
            } else {
                // std::printf("#(%d, %+5.2f) better than (%d, %+5.2f) for TN (%d, %+5.2f)\n",
                //                 tn, chanceOffset, currentBest.tn, currentBest.chanceOffset, normalTN, targetChance);
                                
                // Swap
                currentBest.tn = tn;
                currentBest.chanceOffset = chanceOffset;
            }
        }
        else {
            // std::printf("#(%d, %+5.2f) not considered further\n",
            //             tn, chanceOffset);
        }
    }
    
    return currentBest.tn;
}

int main()
{
    // int overwatchTNs[9][5];
    
    // std::printf("Overwatch TNs:\n");
    // for (int exponent = EXP1; exponent <= EXP9; exponent += 1) {
    //     for (int column = DOUBLE_DISADV; column <= DOUBLE_ADVANTAGE; column += 1) {
    //         const auto tn = GetOptimalOverwatchTNForNormalTN(kNormalTargetNumbers[exponent][column]);
    //         overwatchTNs[exponent][column] = tn;
    //         std::printf("%d, ", tn);
    //     }
    //     std::printf("\n");
    // }
    
    double normalChances[9][5];
    double overwatchChances[9][5];
    double relativeChances[9][5];
    
    // Calculate all
    for (int exponent = EXP1; exponent <= EXP9; exponent += 1) {
        for (int column = DOUBLE_DISADV; column <= DOUBLE_ADVANTAGE; column += 1) {
            const double normalChance    = GetChanceOfMeetingTN(kNormalTargetNumbers[exponent][column]);
            const double overwatchChance = GetChanceOfMeetingTN(kOverwatchTargetNumbers[exponent][column]);
            
            normalChances[exponent][column] = normalChance;
            overwatchChances[exponent][column] = overwatchChance;
            relativeChances[exponent][column] = overwatchChance / normalChance;
        }
    }
    
#define PRINT_TABLE(_table_) \
    do { for (int exponent = EXP1; exponent <= EXP9; exponent += 1) { \
        for (int column = DOUBLE_DISADV; column <= DOUBLE_ADVANTAGE; column += 1) { \
            std::printf("%6.2f%% (%+6.2f%%) | ", \
                        _table_[exponent][column] * 100.0, \
                        (_table_[exponent][column] / _table_[exponent][NORMAL] - 1.0) * 100.0 \
            ); \
        } \
        std::printf("\n"); \
    } } while (false)
    
#define PRINT_TABLE_SIMPLE(_table_) \
    do { for (int exponent = EXP1; exponent <= EXP9; exponent += 1) { \
        for (int column = DOUBLE_DISADV; column <= DOUBLE_ADVANTAGE; column += 1) { \
            std::printf("%6.2f%% | ", _table_[exponent][column] * 100.0); \
        } \
        std::printf("\n"); \
    } } while (false)
    
    std::printf("\nNormal chances:\n");
    PRINT_TABLE(normalChances);

    std::printf("\nOverwatch chances:\n");
    PRINT_TABLE(overwatchChances);
    
    std::printf("\nRelative chances:\n");
    PRINT_TABLE_SIMPLE(relativeChances);

    return 0;
}
```

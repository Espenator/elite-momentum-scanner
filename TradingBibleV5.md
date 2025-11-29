# Trading Bible V5 - Elite Academic Momentum System

> **Structure-First Momentum Trading with VELEZ Validation**
> *Multi-layer signal validation for high-probability setups*

---

## Table of Contents
1. [System Philosophy](#system-philosophy)
2. [Core Methodology](#core-methodology)
3. [VELEZ Validation Framework](#velez-validation-framework)
4. [Signal Layers](#signal-layers)
5. [Entry Rules](#entry-rules)
6. [Exit Strategy](#exit-strategy)
7. [Risk Management](#risk-management)
8. [Daily Workflow](#daily-workflow)

---

## System Philosophy

### The Core Principle
**"Structure precedes momentum. Price respects levels before it respects indicators."**

This system identifies stocks with:
- Strong technical structure (support/resistance)
- Momentum confirmation via VELEZ principles
- Multi-timeframe alignment
- Clean chart patterns

### What Makes This Different
1. **Structure-First**: We find the level, then wait for momentum
2. **Academic Rigor**: Based on proven market microstructure research
3. **Multi-Layer Validation**: No single indicator drives decisions
4. **Automation**: Scanner handles screening, you handle execution

---

## Core Methodology

### The 3-Layer Filter System

```
Layer 1: STRUCTURE    - Key price levels (S/R, pivots, MAs)
Layer 2: MOMENTUM     - VELEZ validation (ADX, RSI, Volume)
Layer 3: CONFIRMATION - Price action at the level
```

### Timeframe Hierarchy

| Timeframe | Purpose | Weight |
|-----------|---------|--------|
| Daily | Trend direction | 40% |
| 4-Hour | Entry timing | 35% |
| 1-Hour | Fine-tuning | 25% |

---

## VELEZ Validation Framework

### The VELEZ Criteria
Based on Oliver Velez's momentum trading principles:

#### 1. ADX Strength
- **Strong Trend**: ADX > 25
- **Optimal Entry**: ADX 20-30 and rising
- **Avoid**: ADX < 20 (choppy market)

#### 2. RSI Positioning
- **Bullish Setup**: RSI 40-60 (room to run)
- **Overbought Caution**: RSI > 70
- **Oversold Bounce**: RSI < 30 (reversal plays only)

#### 3. Volume Confirmation
- **Valid Breakout**: Volume > 1.5x 20-day average
- **Accumulation**: Rising price + rising volume
- **Distribution Warning**: Rising price + falling volume

### VELEZ Score Calculation
```
VELEZ_SCORE = (ADX_Score * 0.4) + (RSI_Score * 0.3) + (Volume_Score * 0.3)

Where:
- ADX_Score: 0-100 based on ADX value and direction
- RSI_Score: 0-100 based on RSI zone
- Volume_Score: 0-100 based on relative volume
```

---

## Signal Layers

### Layer 1: Structure Identification

#### Key Levels to Watch
1. **Previous Day High/Low**
2. **Weekly Pivot Points**
3. **50/200 MA Zones**
4. **Prior Swing Highs/Lows**
5. **Round Numbers** (psychological levels)

#### Structure Quality Score
- Multiple touches = stronger level
- Recent test within 10 days = active level
- Volume at level = significance confirmed

### Layer 2: Momentum Confirmation

#### Bullish Momentum Checklist
- [ ] Price above 20 EMA
- [ ] 20 EMA above 50 SMA
- [ ] ADX > 20 and rising
- [ ] RSI > 50
- [ ] Volume trend positive

#### Bearish Momentum Checklist
- [ ] Price below 20 EMA
- [ ] 20 EMA below 50 SMA
- [ ] ADX > 20 and rising
- [ ] RSI < 50
- [ ] Volume trend positive

### Layer 3: Entry Triggers

#### Valid Entry Signals
1. **Breakout + Retest**: Price breaks level, retests, holds
2. **Bounce Play**: Price tests support/resistance with rejection candle
3. **Momentum Surge**: VELEZ score jumps above 70

---

## Entry Rules

### The 5-Point Entry Checklist

```markdown
Before EVERY trade, confirm:

1. [ ] STRUCTURE: Clear level identified on daily chart
2. [ ] DIRECTION: Multi-timeframe trend alignment
3. [ ] MOMENTUM: VELEZ score > 60
4. [ ] TRIGGER: Price action confirms at level
5. [ ] RISK: Stop loss placed, R:R minimum 2:1
```

### Entry Types

#### Type A: Breakout Entry
- Wait for candle close above resistance
- Enter on first pullback to broken level
- Stop below the breakout candle low

#### Type B: Bounce Entry
- Wait for price to reach key support
- Look for rejection candle (hammer, engulfing)
- Enter on confirmation candle close
- Stop below the swing low

#### Type C: Momentum Entry
- VELEZ score spikes above 75
- Price pulling back to 20 EMA
- Enter when price holds EMA
- Trailing stop from entry

---

## Exit Strategy

### Profit Targets

#### Scale-Out Method
| Exit | Position | Target |
|------|----------|--------|
| 1st | 50% | 1R profit |
| 2nd | 25% | 2R profit |
| 3rd | 25% | Trailing stop |

### Stop Loss Rules

#### Initial Stop Placement
- **Breakout**: Below breakout candle low
- **Bounce**: Below swing low + buffer
- **Momentum**: Below 20 EMA or 1 ATR

#### Trailing Stop Rules
- After 1R: Move stop to breakeven
- After 2R: Trail by 1 ATR
- After 3R: Trail by 20 EMA

---

## Risk Management

### Position Sizing Formula

```
Position Size = (Account Risk $) / (Entry - Stop)

Where:
- Account Risk $ = Account Balance * Risk %
- Risk % = 1-2% per trade (max)
```

### Example Calculation
```
Account: $50,000
Risk per trade: 1% = $500
Entry: $100.00
Stop: $98.00
Risk per share: $2.00

Position Size = $500 / $2.00 = 250 shares
```

### Daily Risk Limits
- **Max daily loss**: 3% of account
- **Max positions**: 5 concurrent
- **Max sector exposure**: 40% in one sector

---

## Daily Workflow

### Pre-Market (Before 9:00 AM)

1. **Run Scanner**
   - Execute Elite Momentum Scanner
   - Review VELEZ scores
   - Identify top 10 candidates

2. **Chart Review**
   - Mark key levels on each candidate
   - Note support/resistance zones
   - Set alerts at entry levels

3. **Plan Trades**
   - Write entry/exit levels
   - Calculate position sizes
   - Set orders if applicable

### Market Hours (9:30 AM - 4:00 PM)

1. **First 30 Minutes**
   - Observe, don't trade (usually)
   - Watch for gaps to fill
   - Note which levels are being tested

2. **Core Trading (10:00 AM - 3:30 PM)**
   - Execute planned setups
   - Follow entry checklist strictly
   - Manage open positions

3. **Last 30 Minutes**
   - Evaluate end-of-day plays
   - Consider closing day trades
   - Prepare swing positions

### Post-Market (After 4:00 PM)

1. **Journal Trades**
   - Record all entries/exits
   - Note what worked/didn't
   - Screenshot setups

2. **Prep Tomorrow**
   - Run evening scan
   - Update watchlist
   - Set overnight alerts

---

## Quick Reference Card

### VELEZ Score Interpretation
| Score | Signal | Action |
|-------|--------|--------|
| 80-100 | Very Strong | Aggressive entry |
| 60-79 | Strong | Standard entry |
| 40-59 | Moderate | Wait for confirmation |
| 0-39 | Weak | No trade |

### Momentum Indicators Quick Check
| Indicator | Bullish | Bearish |
|-----------|---------|----------|
| ADX | > 25, rising | > 25, rising |
| RSI | 40-70 | 30-60 |
| Volume | > 1.5x avg | > 1.5x avg |
| 20/50 EMA | Price above both | Price below both |

---

## Version History

| Version | Date | Changes |
|---------|------|----------|
| V5 | 2025 | Added VELEZ framework, automated scanner integration |
| V4 | 2024 | Multi-timeframe analysis added |
| V3 | 2023 | Risk management refinements |
| V2 | 2022 | Structure-first methodology |
| V1 | 2021 | Initial system creation |

---

**Remember**: *The best trade is the one you don't force. Wait for the setup, execute the plan, manage the risk.*

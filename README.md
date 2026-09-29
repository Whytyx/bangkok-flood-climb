# Bangkok Flood Climb

## V1.7.1 — Jump rocket fix
- Jump is edge-triggered (`jumpLocked` until release) — no sticky re-jump
- Clamp vx/vy; cap moving-platform carry delta (stale `_lx` teleport)
- Softer wind while airborne; knockback clamped
- Clear input on blur / visibilitychange / pointercancel
- Tighter landing snap (no far deck teleport)

## V1.7.0 — Quality & stability
Pools, fair collision, telegraph hazards, themed signs, climbable BTS.

**Live:** https://whytyx.github.io/bangkok-flood-climb/

# 3.0.1
- Divisions now use math.div instead of deprecated literal '/'
- Set min dart sdk to 2.13.0 (down from 2.14.0)
# 3.0.0
- Support null-safety

# 2.0.1
- col min-width now set to 1px (down from 1em)

# 2.0.0
- Breaking change: Mixin includes max-width(), col-padding() & thresholds() removed from grid.css, they must now be explicitly set by client app

# 1.0.1
- Breaking change: Removed theme.css
- Breaking change: Increased `$large-width-threshold` default value to 1100px
- New feature: All constants except `$col-span` can now be overridden by specifying their values before importing grid.css
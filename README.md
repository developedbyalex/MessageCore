# MessageCore

**MessageCore** - A comprehensive Minecraft message management system that needs to be fucking awesome.

## Core Requirements

### Welcome System
- Rank-based welcome messages with permission system
- Configurable first-join celebrations
- Custom join/leave message formatting
- Support for multiple effect types on player join/leave
  - Firework effects with preset patterns
  - Lightning strikes (visual only)
  - Particle systems
  - Sound effects

### Message Formatting
- Full MiniMessage formatting implementation
- Support for gradient colors
- Message centering capabilities
- Multiple display methods:
  - Standard chat
  - Action bar
  - Boss bar with color options
  - Toast notifications
  - Title/subtitle system

### Visual and Audio Integration
- Firework system with:
  - Multiple pattern presets
  - Customizable colors and effects
  - Sequence control
- Sound effect system
- Particle effect system
- Player avatar display capability
- Lightning effect system

### Announcement Framework
- Automated announcement system
- Configurable timing intervals
- Random/sequential ordering options
- Multiple preset support
- Different announcement types in one preset

### Technical Requirements
- YAML-based configuration
- Preset system for effects
- Permission-based controls
- PlaceholderAPI integration
- Performance optimization for effects
- Multi-platform server support

### Configuration Structure
- Main config.yml for core settings
- ranks.yml for permission-based messages
- fireworks.yml for effect presets
- Support for custom sound configurations
- Particle effect definitions

### Message Types Support
- Regular chat messages
- Actionbar messages
- Boss bar messages with customizable colors
- Toast notifications
- Title and subtitle combinations
- Center-aligned messages

## Implementation Notes
- All configurations must support dynamic content through PlaceholderAPI
- Performance optimization required for simultaneous effects
- Maintain compatibility with major server platforms
- Include proper error handling for all effect types
- Implement fail-safes for resource-intensive operations

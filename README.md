## AI Tool Adoption Dashboard

**Author**: Harsh Yadav  



## Overview
This business intelligence dashboard provides comprehensive insights into AI tool adoption patterns across different demographics, industries, and geographical regions. The dashboard tracks key metrics including active users, adoption rates, and usage trends for major AI tools including ChatGPT, Claude, Bard, Midjourney, and Stable Diffusion.

## Data Source

This dashboard is built using the AI Tool Adoption Dataset available on Kaggle. The dataset provides comprehensive information about AI tool usage patterns, user demographics, and adoption trends across various industries and regions.

**Dataset Reference**: [AI Tool Adoption Dataset - Kaggle](https://www.kaggle.com/code/chandradeepnarra3/ai-adoption-visuals/input)

## Key Metrics

### Primary KPIs
- **Active Users**: 731M total active users
- **Adoption Rate**: 7.23M new adoptions
- **Geographic Coverage**: Global usage tracking across multiple countries
- **Industry Penetration**: Analysis across 9+ major industry sectors

## Dashboard Components

### 1. Adoption by Age Group (Sankey Diagram)
- **Purpose**: Visualizes AI tool adoption flow across different age demographics
- **Age Groups Tracked**: 18-24, 25-34, 35-44, 45-54, 55+
- **Tools Analyzed**: ChatGPT, Claude, Bard, Midjourney, Stable Diffusion
- **Insights**: Shows adoption patterns and preferences by generation

### 2. Geographic Distribution (Scatter Plot)
- **Purpose**: Maps AI tool popularity across different countries
- **Countries Included**: USA, Canada, Brazil, UK, Germany, France, India, South Korea, China, Australia
- **Metrics**: User count vs. AI tool adoption correlation
- **Range**: 710K - 740K users across regions

### 3. Active Users by Company Size (Stacked Bar Chart)
- **Purpose**: Analyzes adoption patterns across different company sizes within age groups
- **Categories**: 
  - Increase (Green)
  - Decrease (Red) 
  - Total (Orange)
  - Other (Gray)
- **Scale**: 242M - 246M user range
- **Breakdown**: Segmented by age demographics

### 4. Tool Distribution (Donut Chart)
- **Purpose**: Shows market share of different AI tools
- **Tools Tracked**:
  - ChatGPT (Dominant orange segment)
  - Midjourney (Teal segment)
  - Stable Diffusion (Yellow segment)
  - Bard (Red segment)
  - Claude (Purple segment)

### 5. Industry Adoption (Horizontal Bar Chart)
- **Purpose**: Compares AI tool adoption across industry sectors
- **Industries Analyzed**:
  - Technology (Highest adoption ~950K)
  - Education (~925K)
  - Manufacturing (~900K)
  - Finance (~875K)
  - Transportation (~850K)
  - Healthcare (~825K)
  - Agriculture (~800K)
  - Retail (~775K)
- **Scale**: 900K - 920K adoption range

## Interactive Features

### Filtering Options
The dashboard includes comprehensive filtering capabilities:
- **Company Size**: Filter by organization size
- **Age Group**: Segment analysis by demographic
- **Year**: Historical trend analysis
- **AI Tool**: Focus on specific tools
- **Industry**: Sector-specific insights

### Data Refresh
- Real-time data updates
- Historical trend tracking
- Year-over-year growth analysis (YoY_Growth field available)

## Data Structure

### Core Data Fields
- `adoption_rate`: Numerical adoption metrics
- `age_group`: Demographic categorization
- `ai_tool`: Tool classification
- `company_size`: Organization size categories
- `country`: Geographic identifiers
- `daily_active_users`: Usage frequency metrics
- `industry`: Sector classifications
- `year`: Temporal data points
- `YoY_Growth`: Year-over-year growth calculations

## Key Insights

### Market Leadership
- ChatGPT maintains dominant market position
- Strong adoption across all age groups
- Technology sector leads in AI tool adoption

### Demographic Trends
- Multi-generational adoption with varying tool preferences
- Age-specific usage patterns clearly visible
- Geographic adoption varies significantly by region

### Industry Penetration
- Technology and Education sectors show highest adoption
- Consistent growth across all major industries
- Manufacturing and Finance showing strong enterprise adoption

## Usage Instructions

1. **Navigation**: Use the filter dropdowns at the top to customize your view
2. **Drill-down**: Click on chart elements for detailed breakdowns
3. **Comparison**: Use multiple filters simultaneously for comparative analysis
4. **Export**: Data can be exported for further analysis
5. **Refresh**: Dashboard updates automatically with new data

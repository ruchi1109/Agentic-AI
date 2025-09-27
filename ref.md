# CrewAI Script Analysis - Agents and Tasks Summary

## Overview
- **Total Agents**: 12
- **Total Tasks**: 13

## Agents Details

| # | Agent Variable Name | Role | Primary Focus |
|---|---------------------|------|---------------|
| 1 | `india_job_scraper` | India Job Discovery Specialist | Find and extract job postings from Indian platforms |
| 2 | `job_links_aggregator` | Job Links Collection Specialist | Collect and organize all job links from multiple sources |
| 3 | `india_market_researcher` | India Tech Market Intelligence Analyst | Research Indian tech market trends and salary ranges |
| 4 | `india_company_researcher` | India Company Culture & Background Researcher | Research companies operating in India |
| 5 | `profiler` | Personal Profiler for Engineers | Research job applicants for Indian job market |
| 6 | `resume_strategist` | Resume Strategist for Engineers | Create resumes optimized for Indian market and ATS |
| 7 | `interview_preparer` | Engineering Interview Preparer for Indian Market | Create interview questions based on Indian patterns |
| 8 | `skills_analyzer` | Skills Gap Analysis Expert for Indian Market | Identify skill gaps for Indian job market |
| 9 | `cover_letter_writer` | Cover Letter Specialist for Indian Companies | Create cover letters for Indian hiring managers |
| 10 | `application_strategist` | India Application Strategy Coordinator | Develop strategic approaches for Indian job processes |
| 11 | `network_analyzer` | India Professional Network Analyst | Identify networking opportunities in Indian tech |
| 12 | `application_tracker` | India Application Progress Manager | Track applications with Indian company timelines |

## Agent-Task Mapping

| # | Task Variable Name | Assigned Agent | Agent Role | Output File |
|---|-------------------|----------------|------------|-------------|
| 1 | `india_job_discovery_task` | `india_job_scraper` | India Job Discovery Specialist | - |
| 2 | `job_links_display_task` | `job_links_aggregator` | Job Links Collection Specialist | `india_job_links_directory.md` |
| 3 | `india_market_research_task` | `india_market_researcher` | India Tech Market Intelligence Analyst | - |
| 4 | `india_company_research_task` | `india_company_researcher` | India Company Culture & Background Researcher | - |
| 5 | `india_enhanced_profile_task` | `profiler` | Personal Profiler for Engineers | - |
| 6 | `india_skills_gap_task` | `skills_analyzer` | Skills Gap Analysis Expert for Indian Market | - |
| 7 | `india_job_analysis_task` | `profiler` | Personal Profiler for Engineers | - |
| 8 | `india_resume_task` | `resume_strategist` | Resume Strategist for Engineers | `india_optimized_resumes.md` |
| 9 | `india_cover_letter_task` | `cover_letter_writer` | Cover Letter Specialist for Indian Companies | `india_cover_letters.md` |
| 10 | `india_application_strategy_task` | `application_strategist` | India Application Strategy Coordinator | - |
| 11 | `india_network_analysis_task` | `network_analyzer` | India Professional Network Analyst | - |
| 12 | `india_interview_task` | `interview_preparer` | Engineering Interview Preparer for Indian Market | `india_interview_guide.md` |
| 13 | `india_tracking_task` | `application_tracker` | India Application Progress Manager | `india_application_tracker.md` |

## Agent Workload Distribution

| Agent | Number of Tasks | Tasks Assigned |
|-------|----------------|----------------|
| `india_job_scraper` | 1 | Task 1 |
| `job_links_aggregator` | 1 | Task 2 |
| `india_market_researcher` | 1 | Task 3 |
| `india_company_researcher` | 1 | Task 4 |
| `profiler` | **2** | Tasks 5, 7 |
| `skills_analyzer` | 1 | Task 6 |
| `resume_strategist` | 1 | Task 8 |
| `cover_letter_writer` | 1 | Task 9 |
| `application_strategist` | 1 | Task 10 |
| `network_analyzer` | 1 | Task 11 |
| `interview_preparer` | 1 | Task 12 |
| `application_tracker` | 1 | Task 13 |

## Key Features

### Job Platforms Covered
- Naukri.com
- LinkedIn Jobs India  
- Indeed India
- Instahyre
- Hirist
- AngelList India
- Glassdoor India
- Monster India
- TimesJobs
- Company career pages

### Output Files Generated
1. `india_job_links_directory.md` - Comprehensive job links organized by platform
2. `india_optimized_resumes.md` - Multiple resume versions for different Indian company types
3. `india_cover_letters.md` - India-culturally appropriate cover letter templates
4. `india_interview_guide.md` - Interview preparation specific to Indian companies
5. `india_application_tracker.md` - Application tracking with Indian business timelines

### Execution Phases
1. **Phase 1**: Discovery and Links Display
2. **Phase 2**: Research (Market + Companies + Profile)
3. **Phase 3**: Analysis (Skills + Job Requirements)
4. **Phase 4**: Content Creation (Resumes + Cover Letters)
5. **Phase 5**: Strategy and Preparation (Application + Network + Interview + Tracking)
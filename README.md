# ExamSchedulingForUniversity
Exam Scheduling for University

This repository contains a project for developing an exam scheduling system for a university. The system is implemented using Python and is designed to automate scheduling exams for various courses based on given constraints and assumptions.
Table of Contents

    Introduction
    Features
    Getting Started

Assumptions:

The daily schedule consists of two-time slots:

    morning and noon.
    Exams have a fixed duration of 3 hours.
    The morning slot is scheduled from 9 am to 12 pm, and the noon slot is scheduled from 2 pm to 5 pm.
    It is possible that not all classrooms will be utilized on a given day.
    A higher fitness score indicates a better solution, aiming to maximize the fitness value.
    Days with scheduled exams will have exams in both the morning and noon slots.

Constraints:

    Each course requires an exam to be scheduled.
    Each student is enrolled in at least 3 courses and cannot take more than one exam simultaneously.
    Exams are not scheduled on weekends.
    Exams must be held between 9 am and 5 pm.
    Each exam requires an invigilator, and a teacher cannot invigilate two exams simultaneously.
    A teacher cannot invigilate two consecutive exams.

Introduction

The Exam Scheduling for University project aims to streamline the exam scheduling process for a university by providing an automated system. The system considers various factors such as available time slots, room capacities, student registrations, invigilator assignments, and other constraints to generate an optimized exam schedule.
Features

    Course and student registration management
    Binary encoding of chromosomes for representing solutions
    Fitness function evaluation to assess the quality of solutions
    Roulette wheel selection and crossover operations for generating new solutions
    Support for morning and noon time slots
    Constraints handling course and exam schedule
    CSV export functionality for generated schedules

Getting Started

To get started with the Exam Scheduling for University project, follow these steps:

    Clone the repository:

    Install the required dependencies.

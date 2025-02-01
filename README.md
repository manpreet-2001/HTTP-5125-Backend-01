# HTTP-5125-Backend-01
This repository contains Back-End-Web-Development-1---HTTP-5125.

In this course, I learned server-side web development using C#. I explored how to create data-driven websites and gained hands-on experience in pulling data from various external sources. My skills in building robust web applications with ASP.NET have been further developed, enhancing my ability to create dynamic and interactive websites.

💻 Code Sample
Here's a quick code sample demonstrating how to use the main feature of the project:

// Sample code for Assignment 1
﻿using Microsoft.AspNetCore.Mvc;

namespace Assignment01.Controllers
{
    [Route("api/[controller]")]
    [ApiController]
    public class Q1Controller : Controller
    {
        [HttpGet(template: "welcome")]
        public string welcome()
        {
            return ("Welcome to 5125!");
        }

       
        [HttpGet(template: "example")]
        public string example()
        {
            return ("This is Manpreet Singh");
        }
    }
}

⚠️ Warning
Please ensure you have all necessary dependencies installed before running the project. Refer to the installation instructions in the repository.

ℹ️ Note
This project is open-source and welcomes contributions! Feel free to fork the repository and submit pull requests.

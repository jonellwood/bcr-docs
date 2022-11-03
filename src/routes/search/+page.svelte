<script>    
import search from "../../images/user-search-dashboard.png";
import searchDate from "../../images/user-search-date-picker.png";
import searchDateResult from "../../images/user-search-dates-results.png";
import searchDept from "../../images/user-search-department.png";
import searchDeptResult from "../../images/user-search-department-results.png"
import searchUser from "../../images/user-search-by-user.png";
import searchUserResult from "../../images/user-search-by-user-results.png";
import searchAmount from "../../images/user-search-amount.png";
import searchAmountResult from "../../images/user-search-amount-results.png";
import searchText from "../../images/user-search-text.png";
import searchTextResult from "../../images/user-search-text-with-results.png";
import searchTextNoResult from "../../images/user-search-text-zero-results-copy.png";
</script>
<div class='main'>
    <h1>Using the Search Feature</h1>
    <hr>
    <h2>The Search Dashboard</h2>
    <p>The search Dahsboard will allow you to search for requests in various ways. Each method is accessed via button laid out across the top of the dashboard. The options include Date, Department, User Name, Request Amount, and Text.</p>
    <img src={search} alt="search dashboard" />
    <hr>
    <h2>Search by Date Range</h2>
    <p>Searching by Date Range is as simple as picking a starting and ending date (inclusive) from the date picker. The results are returned in a nice list with easy access to an individual requests.</p>
    <img src={searchDate} alt="sweet date picker" />
    <img src={searchDateResult} alt="results from sweet date picker" />
    <hr>
    <h2>Search by Department</h2>
    <p>Searching by Department starts by picking a Department from the Drop down. The results are returned in a nice list with easy access to an individual requests. Currently all departments are presented in the drop down. This should be a discussion item if we want to continue to allow this behavior in the app. And if so... perhaps the "go to request" button could load a secondary "view only" version of the request IF the department is one not assigned to the user?? </p>
    <img src={searchDept} alt="search by department" />
    <img src={searchDeptResult} alt="results from search by department" />
    <h2>Search by User Name</h2>
    <p>Searching by User is the same as picking a Department from the Drop down. The results are returned in a nice list with easy access to an individual requests. Currently all users requests are presented in the drop down. This should be a discussion item same as above </p>
    <img src={searchUser} alt="search by user" />
    <img src={searchUserResult} alt="result from search by user" />
    <hr>
    <h2>Search By Amount</h2>
    <p>Search by amount needs a starting and ending amount for the range to search by. If you know the dollar amount - use that amount for both.</p>
    <img src={searchAmount} alt="search by amount" />
    <img src={searchAmountResult} alt="restult from search by amount" />
    <hr>
    <h2>Search by Text</h2>
    <p>Search by text allows users to search both the justificaion and comments fields for text strings contained within them. Currently this search method only searches those two items as searching by literally almost every other method is already covered. Keep in mind it is currently an exact match search (case insensitive) - meaning "bir" will not return a result in the example below but "birds" would. </p>
    <p><b>Rest Assured!!!  The dev robots are working hard on improving this. </b></p>    
    <img src={searchText} alt="search by text" />
    <img src={searchTextResult} alt="results of search by text" />
    <img src={searchTextNoResult} alt="results of search by text with no results" />


</div>
<style>
    img{
        margin: 20px;
    }
    .main{
        margin: 30px;
        max-width: 1080px;
    }
</style>
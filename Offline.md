# Offline

## Course
	ID : Unique for each course
	Title
	Description
	Url
	[Not in excel] Pictures (1…n) : Different resolution which can be auto generated)     
	Level
		From Provider: Beginner, intermediate, advanced
		[Not in excel] Level Calculated: Based on feedback

	Instructors {1…n} : There can be multiple instructor for a course : Can be refactored to a separate set/table
		[Not in excel] ID 
		Name
		Title
		Linkedin url
		Website
		[Not in excel] Pictures (1…n) : different resolution which can be auto generated
		Company Id : Can be refactored to a separate set/table
		Company Name    
		[Not in excel] Ranking : Calculated from feedback
		[Not in excel] Feedback
			Scale from 1-10
			Verbal
					
	Price
		[Not in excel] Mode of payment
		Currency
		Price
		[Not in excel] Max price
		[Not in excel] Min price
		[Not in excel] Bulk order pricing
			TBD: Pricing model for bulk licensing like PLURALSIGHT
		Max student
		Min Student
	Follow up assessment (1..n)    : Depends on schedule of course
		Is Assessment required
			[Not in excel] TBD: schema of assessment and result of assessment per student
			[Not in excel] TBD: Can be refactored to a separate set/table
	
	Prerequisites
	[Not in excel] Chat / Forum for the duration of the course
	[Not in excel] Feedback
	
	[Not in excel] Feedback from: (1…n)
			Attendee
			Value add Scale from 1-10
			Verbal
			Difficulty level (used for adjusting level automatically)
			Expertise level
			Content quality
			Instructor quality
			Venue
			Streaming quality
			Learning type  
			Tag
			Question for instructors

	Tag   : For categorisation, recommendation engine
		{ Tag for categorisation from vendor, weight } - Primary - Secondary weights will defer
		[Not in excel] { Tag based on feedback from students to further optimise our categorisation, weight}
		[Not in excel] { Tag generated from course content, weight}

	
	Location:
		Is Available on trainer location [if false then on company location]
		Primary Cities
		
	Schedule
		Duration
		[Not in excel] Start date  (auto calculated by using calender)
		[Not in excel] End date    (auto calculated by using calender)
		IsRecurring
			RecurringIn
			NumberOfTimeRecurring
	[Not in excel] Expiry date (when course will no longer be active)

	Min student count	
	Max student count

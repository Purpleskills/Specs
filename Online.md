# Online

## Course
	ID : Unique for each course
	Title
	Description
	Url
	Pictures (1…n) : different resolution which can be auto genetrated)     
	Level
		From Provider: Beginner, intermediate, advanced
		[Not in excel] Level Calculated: Based on feedback


	Instructors {1…n} : Multiple instructor to a course   : Can be refactored to a separate set/table
		ID
		Name
		Title
		Linkedin url
		Website
		Pictures (1…n) : different resolution which can be auto genetrated
		Company Id : Can be refactored to a separate set/table
		Company Name    
		Ranking : Calculated from feedback
		Feedback
			Scale from 1-10
			Verbal
					
	Price
		Mode of payment
		Currency
		Price
		Max price
		Min price
		Bulk order pricing
			TBD: Pricing model for bulk licensing like PLURALSIGHT
	
	Follow up assessment (1..n)    : Depends on schedule of course
		Is Assessment required
			TBD: schema of assessment and result of assessment per student
			TBD: Can be refactored to a separate set/table

	Prerequisites
		[Not in excel] Chat / Forum for the duration of the course
		[Not in excel] Feedback

	Style of learning (interactive with a group, individual)
	Schedule
		Start date
		Expiry date (when course will no longer be active)
		Duration
	
	Feedback
		Feedback from: (1…n)
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
			Question for instructor

	Tag   : For categorisation, recommendation engine
		{ Tag for categorisation from vendor, weight } - Primary - Secondary weights will defer
		{ Tag from students to further optimise our categorisation, weight}
		{ Tag from course content, weight}

	Expiry date (when course will no longer be active)

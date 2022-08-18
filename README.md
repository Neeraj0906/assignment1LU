<form action="portfolio.html" method="post">
    <div class="Name">
      <label for="name">Name</label>
      <input type="text" id="name" name="my_name" placeholder="S.Neeraj" pattern=[A-Z\sa-z]{3,20} required>
    </div>
    <div class="Email">
      <label for="email">E-mail</label>
      <input type="email" id="email" name="my_email" placeholder="eng20cs0301.neeraj@email.com" required>
    </div>
    <div class="phone number">
      <label for="phone">Phone</label>
      <input type="tel" id="phone" name="my_phone" placeholder="6382561931" pattern=(\d{3})-?\s?(\d{3})-?\s?(\d{4}) required>
    </div>
    <hr>
    <div class="age">
      <label for="Age">Age</label>
      <input type="number" id="age" name="current_age" placeholder="20" min="1" required>
    </div>
    <div class="strengths">
      <label for="strength">Strength</label>
      <input type="char" id="strength" placeholder="managing_time , physical_activities , understanding_things , communication , fast_learner , logical_thinking"  min="0" required>
    </div>
    <div class="weakness">
      <label for="weakness">Weakness</label>
      <input type="char" placeholder="face difficulty when i code , bad handwriting" name="weakness" required>
    </div>
    <div class="interested_companies">
      <label for="companies">Companies</label>
      <select id="companies" name="company" required>
          <option value="">companies i like are in the List</option>
          <option value="1st_preference">google</option>
          <option value="2nd_preference">microsoft</option>
          <option value="3rd_preference">amazon</option>
      </select>
    </div>
    <hr>
    <div class="college">
        <label for="college">Content</label>
        <select id="college" name="college" required>
            <option value="">me in college</option>
            <option value="program">Btech</option>
            <option value="course">cse</option>
            <option value="Aim">FullStackDevelopment</option>
        </select>
     <div class="projects">
        <label for ="projects">projects</label>
        <select id="projects" name="classification of diabetic retinopathy using CNN and deep learning" required>
            <option value ="year">2nd year BTech</option>
            <option value ="">project name</option>
            <option value ="">classification of diabetic retinopathy using CNN and deep learning</option>
        </select>
    
  </form>

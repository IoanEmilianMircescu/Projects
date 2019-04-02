public class Guest {
	private String firstName;
	private String lastName;
	private String email;
	private String phoneNumber;
	
	public Guest (String firstName, String lastName, String email, String phoneNumber) {
		this.firstName = firstName;
		this.lastName = lastName;
		this.email = email;
		this.phoneNumber = phoneNumber;
	}
	public String getFirstName() {
		return this.firstName;
	}
	public void setFirstName(String firstName) {
		this.firstName = firstName;
	}
	public String getLastName() {
		return this.lastName;
	}
	public void setLastName (String lastName) {
		this.lastName = lastName;
	}
	public String getEmail() {
		return this.email;
	}
	public void setEmail(String email) {
		this.email = email;
	}
	public String getPhoneNumber() {
		return this.phoneNumber;
	}
	public void setPhoneNumber (String phoneNumber) {
		this.phoneNumber = phoneNumber;
	}
	@Override
	public String toString() {
		return ". Nume: " + this.firstName + " " + this.lastName + ", Email: " + this.email + ", Telefon: " + this.phoneNumber;
	}
	@Override
	public boolean equals(Object obj) {
		if (this == obj) { // if the references are the same, then the object is the same.
			return true;
		}
		if (obj == null) {
			return false;
		}
		if (this.getClass() == obj.getClass()) {
			return false;
		}
		Guest guestObj = (Guest) obj; // downcasting of the Object obj to the Guest class;
		if (this.email == guestObj.email && this.phoneNumber == guestObj.phoneNumber) { // is super.equals(guestObj) really necessary???
			return true;
		}
		return false;
	}
}

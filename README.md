# SearchableSpinner 
[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-SearchableSpinner-green.svg?style=true)](https://android-arsenal.com/details/1/3272)

Spinner with searchable items.

Searchable Spinner is a dialog spinner with the search feature which allows to search the items loaded in the spinner.

![Alt text](https://github.com/miteshpithadiya/SearchableSpinner/blob/master/searchablespinnerlibrary/src/main/res/nobleltevzwLMY47XMeditab02192016201518.gif "Searchable Spinner")

# Maven rep
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
    
# Gradle
    dependencies {
        ...
	    implementation 'com.github.ex1usive-m4d:searchable-spinner:1.01'
    }

# Usage
    <com.toptoche.searchablespinnerlibrary.SearchableSpinner
            android:layout_width="wrap_content"
            android:layout_height="wrap_content" />

    searchableSpinner.setTitle("Select Item");
    searchableSpinner.setPositiveButton("OK");
    

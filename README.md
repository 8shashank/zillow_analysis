## Introduction
Zillow Analysis project is for looking up real estate trends in the location of your choice(assuming that location is in the list below).

This uses the public data from Zillow here(https://www.zillow.com/research/data/) to generate a report for specified metro location(s). 

Caching is used when fetching the data files to speed up subsequent executions and to avoid making unnecessary web requests.

## Screenshot:
![image](https://user-images.githubusercontent.com/4637055/166850254-f0e0474e-15d2-47ab-838e-c866cc9a1a29.png)

## Valid Locations
These are the locations I've seen in Zillow data that you can query on. Partial matches are enabled, so you could just use city name assuming it is unique.

New York, NY

Los Angeles-Long Beach-Anaheim, CA

Chicago, IL

Dallas-Fort Worth, TX

Philadelphia, PA

Houston, TX

Washington, DC

Miami-Fort Lauderdale, FL

Atlanta, GA

Boston, MA

San Francisco, CA

Detroit, MI

Riverside, CA

Phoenix, AZ

Seattle, WA

Minneapolis-St Paul, MN

San Diego, CA

St. Louis, MO

Tampa, FL

Baltimore, MD

Denver, CO

Pittsburgh, PA

Portland, OR

Charlotte, NC

Sacramento, CA

San Antonio, TX

Orlando, FL

Cincinnati, OH

Cleveland, OH

Kansas City, MO

Las Vegas, NV

Columbus, OH

Indianapolis, IN

San Jose, CA

Austin, TX

Virginia Beach, VA

Nashville, TN

Providence, RI

Milwaukee, WI

Jacksonville, FL

Memphis, TN

Oklahoma City, OK

Louisville-Jefferson County, KY

Hartford, CT

Richmond, VA

New Orleans, LA

Buffalo, NY

Raleigh, NC

Birmingham, AL

Salt Lake City, UT

Rochester, NY

Grand Rapids, MI

Tucson, AZ

Urban Honolulu, HI

Tulsa, OK

Fresno, CA

Worcester, MA

Stamford, CT

Albuquerque, NM

Albany, NY

Omaha, NE

New Haven, CT

Bakersfield, CA

Knoxville, TN

Greenville, SC

Ventura, CA

Allentown, PA

El Paso, TX

Baton Rouge, LA

Dayton, OH

McAllen, TX

Columbia, SC

Greensboro, NC

Akron, OH

North Port-Sarasota-Bradenton, FL

Little Rock, AR

Stockton, CA

Charleston, SC

Syracuse, NY

Colorado Springs, CO

Winston-Salem, NC

Wichita, KS

Springfield, MA

Fort Myers, FL

Boise City, ID

Toledo, OH

Madison, WI

Lakeland, FL

Ogden, UT

Daytona Beach, FL

Des Moines, IA

Jackson, MS

Youngstown, OH

Augusta, GA

Scranton, PA

Harrisburg, PA

Melbourne, FL

Chattanooga, TN

Spokane, WA

Provo, UT

Lancaster, PA

Modesto, CA

Portland, ME

Durham, NC

Santa Rosa, CA

Lexington, KY

Lafayette, LA

Lansing, MI

Fayetteville, AR

Pensacola, FL

Visalia, CA

Shreveport, LA

Springfield, MO

York, PA

Corpus Christi, TX

Flint, MI

Reno, NV

Asheville, NC

Port St. Lucie, FL

Santa Maria-Santa Barbara, CA

Huntsville, AL

Fort Wayne, IN

Salinas, CA

Vallejo, CA

Mobile, AL

Reading, PA

Brownsville, TX

Killeen, TX

Canton, OH

Beaumont, TX

Manchester, NH

Salem, OR

Anchorage, AK

Davenport, IL

Peoria, IL

Myrtle Beach, SC

Montgomery, AL

Salisbury, MD

Gulfport, MS

Tallahassee, FL

Trenton, NJ

Fayetteville, NC

Hickory, NC

Huntington, WV

Eugene, OR

Rockford, IL

Savannah, GA

Ann Arbor, MI

Ocala, FL

Kalamazoo, MI

Naples, FL

South Bend, IN

Spartanburg, SC

Evansville, IN

Kingsport, TN

Roanoke, VA

Green Bay, WI

Lincoln, NE

Fort Collins, CO

Utica, NY

Columbus, GA

Boulder, CO

Lubbock, TX

Erie, PA

Fort Smith, AR

Duluth, MN

Atlantic City, NJ

New London, CT

San Luis Obispo, CA

Gainesville, FL

Santa Cruz, CA

Clarksville, TN

Cedar Rapids, IA

Merced, CA

Wilmington, NC

Kennewick, WA

Greeley, CO

Waco, TX

Olympia, WA

Amarillo, TX

Binghamton, NY

Hagerstown, WV

Bremerton, WA

Laredo, TX

Lynchburg, VA

Yakima, WA

Crestview-Fort Walton Beach-Destin, FL

Topeka, KS

Macon-Bibb County, GA

Champaign-Urbana, IL

Tuscaloosa, AL

College Station, TX

Sioux Falls, SD

Charleston, WV

Appleton, WI

Chico, CA

Charlottesville, VA

Claremont, NH

Barnstable Town, MA

Longview, TX

Burlington, VT

Prescott, AZ

Springfield, IL

Tyler, TX

Las Cruces, NM

Fargo, ND

Houma, LA

Rochester, MN

Florence, SC

Medford, OR

Lafayette-West Lafayette, IN

Bellingham, WA

Lake Havasu City, AZ

Saginaw, MI

Lake Charles, LA

Johnson City, TN

Elkhart, IN

Yuma, AZ

Racine, WI

Athens, GA

Torrington, CT

St. Cloud, MN

Hilton Head Island, SC

Bloomington, IL

Hilo, HI

Panama City, FL

Kingston, NY

Daphne, AL

Gainesville, GA

Warner Robins, GA

Blacksburg, VA

Jacksonville, NC

Redding, CA

Monroe, LA

Joplin, MO

El Centro, CA

Terre Haute, IN

Muskegon, MI

East Stroudsburg, PA

Sioux City, IA

Greenville, NC

Waterloo, IA

Oshkosh, WI

Yuba City, CA

Abilene, TX

Columbia, MO

Dover, DE

Eau Claire, WI

Janesville, WI

Jackson, MI

Punta Gorda, FL

Bloomington, IN

Pueblo, CO

Billings, MT

Bowling Green, KY

Bend, OR

Albany, GA

Vineland, NJ

Niles, MI

Kahului, HI

Ottawa, IL

State College, PA

Bangor, ME

Alexandria, LA

Decatur, AL

Hanford, CA

Iowa City, IA

Rocky Mount, NC

Monroe, MI

Wichita Falls, TX

Burlington, NC

Madera, CA

Jefferson City, MO

Chambersburg, PA

Texarkana, TX

Elizabethtown, KY

Pottsville, PA

Wheeling, OH

Florence, AL

Grand Junction, CO

Concord, NH

Dothan, AL

Santa Fe, NM

Johnstown, PA

Traverse City, MI

Hattiesburg, MS

Dalton, GA

Midland, TX

Homosassa Springs, FL

Auburn, AL

Valdosta, GA

Coeur d'Alene, ID

Springfield, OH

St. George, UT

Vero Beach, FL

Odessa, TX

Napa, CA

Tupelo, MS

Battle Creek, MI

Jamestown, NY

Eureka, CA

Rapid City, SD

Flagstaff, AZ

Lumberton, NC

Wausau, WI

La Crosse, WI

Lebanon, PA

Idaho Falls, ID

Sierra Vista, AZ

Pittsfield, MA

Lawton, OK

Farmington, NM

Jackson, TN

Morgantown, WV

Glens Falls, NY

Winchester, VA

St. Joseph, MO

Altoona, PA

New Bern, NC

Carbondale, IL

London, KY

Logan, ID

Harrisonburg, VA

Beckley, WV

Mansfield, OH

Weirton, OH

Goldsboro, NC

Augusta, ME

Hammond, LA

Jonesboro, AR

Sherman, TX

Anniston, AL

Staunton, VA

Muncie, IN

Mount Vernon, WA

Albany, OR

Watertown, NY

Williamsport, PA

Cleveland, TN

Sheboygan, WI

Bismarck, ND

Owensboro, KY

Dunn, NC

Wooster, OH

Morristown, TN

Kankakee, IL

Brunswick, GA

Ogdensburg, NY

San Angelo, TX

Michigan City, IN

Holland, MI

Wenatchee, WA

Lawrence, KS

Decatur, IL

Missoula, MT

Salem, OH

Bay City, MI

Lewiston, ME

Roseburg, OR

Sumter, SC

Show Low, AZ

Meridian, MS

Bluefield, WV

Danville, VA

Lima, OH

Cookeville, TN

California-Lexington Park, MD

Gadsden, AL

Cumberland, MD

Longview, WA

Whitewater, WI

Fond du Lac, WI

Ithaca, NY

Ashtabula, OH

Gettysburg, PA

Pine Bluff, AR

Tullahoma, TN

Richmond, KY

Adrian, MI

Twin Falls, ID

Corning, NY

Sebring, FL

Truckee, CA

Paducah, KY

Grand Forks, ND

Shelby, NC

Fairbanks, AK

Ocean City, NJ

Mankato, MN

Rome, GA

Cape Girardeau, MO

Hot Springs, AR

Greenwood, SC

Sunbury, PA

Clarksburg, WV

Victoria, TX

Talladega, AL

Dubuque, IA

The Villages, FL

Albertville, AL

Manhattan, KS

Parkersburg, WV

New Philadelphia, OH

Orangeburg, SC

Cheyenne, WY

New Castle, PA

Brainerd, MN

Kalispell, MT

Sevierville, TN

Ames, IA

Bozeman, MT

Moses Lake, WA

Indiana, PA

Elmira, NY

Meadville, PA

Beaver Dam, WI

Pinehurst-Southern Pines, NC

Ukiah, CA

Hermiston-Pendleton, OR

Lufkin, TX

Zanesville, OH

Corvallis, OR

Bloomsburg, PA

Laurel, MS

Russellville, AR

Branson, MO

Watertown, WI

Midland, MI

Opelousas, LA

Pocatello, ID

Kokomo, IN

Grants Pass, OR

Huntsville, TX

Plattsburgh, NY

Grand Island, NE

DuBois, PA

Danville, IL

Manitowoc, WI

Great Falls, MT

Wilson, NC

Cullman, AL

Olean, NY

Auburn, NY

Portsmouth, OH

Athens, TX

Oak Harbor, WA

Chillicothe, OH

Hinesville, GA

Somerset, PA

Warsaw, IN

Stillwater, OK

Quincy, IL

Keene, NH

Sandusky, OH

Searcy, AR

Columbus, IN

Roanoke Rapids, NC

Centralia, WA

Casper, WY

Helena, MT

Findlay, OH

Wisconsin Rapids-Marshfield, WI

Palatka, FL

Seneca, SC

Mount Airy, NC

Glenwood Springs, CO

Key West, FL

Aberdeen, WA

Gallup, NM

Port Angeles, WA

Greenfield Town, MA

Muskogee, OK

Frankfort, KY

Owosso, MI

Mount Pleasant, MI

Statesboro, GA

Marion, IN

Stevens Point, WI

Minot, ND

Shawnee, OK

North Wilkesboro, NC

Richmond, IN

Greeneville, TN

Martinsville, VA

Forest City, NC

Lake City, FL

Kapaa, HI

Marquette, MI

LaGrange, GA

Marion, OH

Morehead City, NC

Klamath Falls, OR

Marinette, WI

Roswell, NM

Marshall, TX

Farmington, MO

Charleston, IL

Athens, OH

Hobbs, NM

Clearlake, CA

Nacogdoches, TX

Hutchinson, KS

Faribault, MN

Elizabeth City, NC

Ionia, MI

Alamogordo, NM

Red Bluff, CA

Hudson, NY

Somerset, KY

Coos Bay, OR

Walla Walla, WA

Sayre, PA

Oneonta, NY

Fort Madison, IA

Baraboo, WI

Marietta, OH

Salina, KS

Rutland, VT

Big Stone Gap, VA

Sturgis, MI

Rio Grande City, TX

Fremont, OH

Mount Vernon, OH

Lewiston, ID

Shelton, WA

Albemarle, NC

Enid, OK

Jefferson, GA

Georgetown, SC

Laconia, NH

Batavia, NY

Oxford, NC

Columbus, MS

Norwalk, OH

Barre, VT

Kinston, NC

Sterling, IL

Palestine, TX

Dublin, GA

Vicksburg, MS

Point Pleasant, WV

Sanford, NC

Fergus Falls, MN

Tiffin, OH

Fairmont, WV

Crossville, TN

Picayune, MS

Gloversville, NY

Sonora, CA

Gaffney, SC

Carson City, NV

Calhoun, GA

Milledgeville, GA

Waycross, GA

Oil City, PA

Jasper, IN

Morgan City, LA

Eagle Pass, TX

Ontario, OR

Carlsbad, NM

Payson, AZ

McComb, MS

Rochelle, IL

Scottsboro, AL

Danville, KY

Ashland, OH

Natchez, MS

Greenville, OH

Galesburg, IL

Warrensburg, MO

Kearney, NE

Fort Polk South, LA

Fort Leonard Wood, MO

Glasgow, KY

Athens, TN

Edwards, CO

Fernley, NV

Mason City, IA

Malone, NY

Winona, MN

Durango, CO

Platteville, WI

Greenville, MS

Boone, NC

Bartlesville, OK

Jacksonville, TX

Elko, NV

Rexburg, ID

St. Marys, GA

Ozark, AL

Amsterdam, NY

Enterprise, AL

Paris, TX

Kerrville, TX

New Castle, IN

Sidney, OH

Cortland, NY

Clinton, IA

Del Rio, TX

Clovis, NM

Norfolk, NE

Washington, NC

Corsicana, TX

Freeport, IL

Starkville, MS

Burlington, IA

Cadillac, MI

Ardmore, OK

Kendallville, IN

Nogales, AZ

Oxford, MS

Bogalusa, LA

Plymouth, IN

Gardnerville Ranchos, NV

Tahlequah, OK

Madisonville, KY

CaÃ±on City, CO

Ruston, LA

Hillsdale, MI

Lewistown, PA

Rockingham, NC

Ponca City, OK

Blytheville, AR

Red Wing, MN

Shawano, WI

Cedar City, UT

Bedford, IN

Gillette, WY

Newport, OR

Wapakoneta, OH

Huntingdon, PA

Bellefontaine, OH

McAlester, OK

Blackfoot, ID

Moultrie, GA

Henderson, NC

Coldwater, MI

Harrison, AR

Rolla, MO

Shelbyville, TN

Duncan, OK

Marion, NC

Lewisburg, PA

Pullman, WA

Thomasville, GA

Bemidji, MN

Mount Sterling, KY

Ottumwa, IA

Pahrump, NV

Menomonie, WI

Selma, AL

Rock Springs, WY

Bucyrus, OH

Bradford, PA

Bardstown, KY

Cornelia, GA

Burley, ID

Greenwood, MS

Big Rapids, MI

Poplar Bluff, MO

Muscatine, IA

Alma, MI

Durant, OK

Seymour, IN

Douglas, GA

Willmar, MN

Auburn, IN

Sedalia, MO

Paragould, AR

Wilmington, OH

Lawrenceburg, TN

Warren, PA

El Dorado, AR

Mountain Home, AR

Cedartown, GA

Port Clinton, OH

El Campo, TX

Montrose, CO

Ellensburg, WA

Jacksonville, IL

Sandpoint, ID

Alice, TX

Celina, OH

Garden City, KS

Marshalltown, IA

Aberdeen, SD

West Plains, MO

Cullowhee, NC

EspaÂ±ola, NM

Riverton, WY

Tifton, GA

Urbana, OH

Cambridge, OH

Okeechobee, FL

McMinnville, TN

Selinsgrove, PA

Natchitoches, LA

Centralia, IL

Berlin, NH

Lock Haven, PA

Sikeston, MO

Austin, MN

Clewiston, FL

Pittsburg, KS

Defiance, OH

Scottsbluff, NE

Logansport, IN

Pontiac, IL

Hannibal, MO

Mount Vernon, IL

Houghton, MI

Union City, TN

Sault Ste. Marie, MI

Vincennes, IN

Gainesville, TX

Dyersburg, TN

Kill Devil Hills, NC

Crawfordsville, IN

Brownwood, TX

Stephenville, TX

Americus, GA

Easton, MD

North Platte, NE

Newberry, SC

Ada, OK

Moscow, ID

Safford, AZ

Murray, KY

Bennington, VT

Huntington, IN

Mayfield, KY

Escanaba, MI

Canton, IL

Corinth, MS

Astoria, OR

Peru, IN

Coshocton, OH

Newton, IA

Logan, WV

Bay City, TX

Fremont, NE

Hutchinson, MN

Batesville, AR

Owatonna, MN

Vidalia, GA

Summit Park, UT

Arkansas City-Winfield, KS

Laramie, WY

Plainview, TX

Big Spring, TX

Laurinburg, NC

Dixon, IL

Alexandria, MN

Newport, TN

DeRidder, LA

Lebanon, MO

Coffeyville, KS

Seneca Falls, NY

Sulphur Springs, TX

Martin, TN

Susanville, CA

Brookhaven, MS

Arcadia, FL

Taylorville, IL

Decatur, IN

Junction City, KS

Effingham, IL

Valley, AL

Butte, MT

Angola, IN

Cleveland, MS

Dodge City, KS

Brenham, TX

Emporia, KS

Jackson, OH

Frankfort, IN

Brevard, NC

Taos, NM

Malvern, AR

Troy, AL

Wabash, IN

Cambridge, MD

Macomb, IL

Vernal, UT

Kingsville, TX

Madison, IN

Mount Pleasant, TX

Paris, TN

Columbus, NE

Brookings, SD

Kennett, MO

Beeville, TX

Miami, OK

Dayton, TN

Washington, IN

Camden, AR

Jackson, WY

Hastings, NE

Juneau, AK

Albert Lea, MN

Lewisburg, TN

Iron Mountain, MI

Lincoln, IL

Jesup, GA

Kirksville, MO

Alpena, MI

Silver City, NM

Indianola, MS

Elkins, WV

Las Vegas, NM

McPherson, KS

Sheridan, WY

Washington Court House, OH

Bennettsville, SC

Van Wert, OH

Merrill, WI

Ludington, MI

Middlesborough, KY

Crescent City, CA

North Vernon, IN

Hays, KS

Forrest City, AR

Fort Morgan, CO

Mineral Wells, TX

Breckenridge, CO

Bastrop, LA

Bainbridge, GA

Wauchula, FL

Hailey, ID

Great Bend, KS

Weatherford, OK

Watertown, SD

Grants, NM

Thomaston, GA

Mountain Home, ID

Altus, OK

Uvalde, TX

Lexington, NE

Boone, IA

Toccoa, GA

Clarksdale, MS

Summerville, GA

Ottawa, KS

New Ulm, MN

Marshall, MN

La Grande, OR

Greensburg, IN

Mexico, MO

Moberly, MO

The Dalles, OR

Deming, NM

Fallon, NV

Fredericksburg, TX

Magnolia, AR

Campbellsville, KY

Connersville, IN

Dickinson, ND

Spearfish, SD

Heber, UT

Steamboat Springs, CO

Cordele, GA

Maryville, MO

Marshall, MO

Arkadelphia, AR

Liberal, KS

Levelland, TX

Wahpeton, ND

Mitchell, SD

Sterling, CO

Pampa, TX

Yankton, SD

Williston, ND

Oskaloosa, IA

Brookings, OR

Hood River, OR

Beatrice, NE

Borger, TX

Raymondville, TX

Elk City, OK

Grenada, MS

Dumas, TX

Helena, AR

Parsons, KS

Price, UT

Port Lavaca, TX

Worthington, MN

Pierre, SD

Evanston, WY

Jamestown, ND

Prineville, OR

Guymon, OK

Storm Lake, IA

Woodward, OK

Portales, NM

Hereford, TX

Othello, WA

Los Alamos, NM

Fitzgerald, GA

Maysville, KY

Huron, SD

Atchison, KS

Snyder, TX

Fairfield, IA

Spencer, IA

Spirit Lake, IA

Vineyard Haven, MA

Winnemucca, NV

Sweetwater, TX

Andrews, TX

Zapata, TX

Vermillion, SD

Lamesa, TX

Craig, CO

Pecos, TX

Vernon, TX

Ketchikan, AK
